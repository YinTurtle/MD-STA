## What Are Enzymes? The Basics

### Definition & Core Properties

**Enzymes are biological catalysts made of proteins** that speed up reactions without being consumed.

**The Lock-and-Key Analogy**: Think of enzymes as specialized tools - each one designed for a specific job. The enzyme (lock) only works with its specific substrate (key).

**Key characteristics:**

- **Not altered** by the reaction - recycled and reused
- **Lower activation energy** - make reactions happen faster by stabilizing the transition state (the high-energy intermediate)
- **Operate under body conditions** - 37°C, neutral pH, aqueous environment
- **Form enzyme-substrate complexes (ES)** at the active site
- **Highly specific** - usually one enzyme, one reaction, one substrate
- **Can be regulated** - activity turned up or down as needed

**The Reaction**: E + S ⇌ ES → EP → E + P

- E = Enzyme
- S = Substrate
- ES = Enzyme-Substrate complex
- P = Product

### Why This Matters Clinically

**Enzymes are incredibly powerful:**

- Some increase reaction rates by **10¹⁰ to 10¹⁷ fold**
- Example: Orotidine decarboxylase increases rate 10¹⁷ times - a reaction that would take 78 million years happens in seconds!

---

## Clinical Relevance: Why You Need to Know This

### 1. **Disease Diagnosis**

**Enzyme levels in blood = diagnostic markers**

**Example: Myocardial Infarction (Heart Attack)**

- Damaged heart muscle releases enzymes into bloodstream
- **Troponins, CK-MB (creatine kinase-MB)** - elevated levels confirm MI
- **Key point**: You're not just measuring if the enzyme is present, but its _concentration and activity_

**Other examples:**

- Liver disease → elevated ALT, AST, ALP
- Pancreatitis → elevated amylase, lipase
- Bone disease → elevated alkaline phosphatase

### 2. **Genetic Enzyme Deficiencies**

**"Inborn errors of metabolism"** - missing or defective enzymes cause disease

**Example: Phenylketonuria (PKU)**

- Missing enzyme: **phenylalanine hydroxylase**
- Can't convert phenylalanine → tyrosine
- Phenylalanine accumulates → brain damage
- **Treatment**: Dietary restriction (avoid phenylalanine)
- **Detected on**: Newborn screening (heel prick test)

**Other examples to know:**

- Galactosemia
- G6PD deficiency (causes hemolytic anemia with certain drugs/foods)
- Lactose intolerance (lactase deficiency)

### 3. **Drug Therapy**

**Most drugs work by inhibiting enzymes!**

Understanding enzyme kinetics tells us:

- **How much drug to give** (dosage)
- **How often to give it** (based on mechanism)
- **Drug interactions** (competitive inhibition)
- **Side effects** (off-target enzyme inhibition)

---

## Measuring Enzyme Activity: The Fundamentals

### Initial Velocity (v₀) - The Only Valid Measurement

**Why only measure the start of the reaction?**

Think of a race: At the start, everyone runs at their top speed. As time goes on:

- Runners get tired (enzyme denatures)
- The finish line gets crowded (products accumulate and inhibit)
- Fewer runners at the start line (substrate depletes)
- Some runners start walking backwards (reverse reaction)

**Therefore**: Measure **v₀ (initial velocity)** = rate at the very beginning when:

- [Substrate] is essentially constant
- [Product] ≈ 0
- Enzyme is fresh
- Forward reaction dominates

### The Experimental Setup

**How to measure enzyme activity:**

1. Add enzyme to substrate
2. At different time points, measure product formation
3. Plot [Product] vs time
4. The slope at the very beginning = v₀
5. Repeat with different substrate concentrations

---

## Michaelis-Menten Kinetics: Understanding Enzyme Behavior

### The Hyperbolic Curve

![[Pasted image 20251016001519.png]]


**What this curve tells us:**
- At **low [S]**: Enzyme has spare capacity - doubling substrate doubles velocity (first-order kinetics)
- At **high [S]**: Every enzyme molecule is busy - enzyme is **saturated** - reached Vmax (zero-order kinetics)

### The Michaelis-Menten Equation

**v₀ = (Vmax × [S]) / (Km + [S])**

**Don't panic!** You don't need to derive this, but understand what each term means:

- **v₀** = initial velocity (what you measure)
- **Vmax** = maximum velocity (when all enzyme active sites are occupied)
- **[S]** = substrate concentration (what you vary)
- **Km** = Michaelis constant (the key parameter!)

---

## Km: The Most Important Number

### What Is Km?

**Km = the substrate concentration needed to reach half-maximal velocity (Vmax/2)**

**Mathematical proof (you should understand this logic):**
When v₀ = Vmax/2:

Vmax/2 = (Vmax × [S]) / (Km + [S])

Cancel Vmax, multiply both sides by (Km + [S]):
(Km + [S])/2 = [S]

Therefore: **Km = [S]**

### What Km Tells You Clinically

**Km is a measure of enzyme-substrate affinity:**
- **Low Km** = high affinity = enzyme grabs substrate easily = works at LOW substrate concentrations
- **High Km** = low affinity = enzyme needs LOTS of substrate to work efficiently

### Clinical Example: Hexokinase vs Glucokinase

Both phosphorylate glucose (Glucose → Glucose-6-Phosphate) using ATP, but serve **different physiological roles**:

**Hexokinase:**
- **Km = 0.1 mM** (very low!)
- **Normal blood glucose = 5 mM** (50× higher than Km)
- **Location**: All tissues
- **Function**: Energy production for cells
- **Clinical significance**: Even when blood glucose drops, hexokinase keeps working because its Km is so low - ensures cells get energy even during fasting

**Glucokinase:**
- **Km = 50 mM** (high - close to blood glucose level!)
- **Location**: Liver (and pancreatic β-cells)
- **Function**: Glucose storage as glycogen
- **Clinical significance**: Only works when blood glucose is HIGH (after meals) - acts as a "glucose sensor"
  - When glucose is low (5 mM), glucokinase barely works → glucose stays in blood
  - When glucose is high (>10 mM), glucokinase activates → removes glucose for storage

**The Brilliant Design**: This ensures glucose is available for essential tissues (brain, RBCs) during fasting, and only stored when abundant!

**Clinical pearl**: Glucokinase mutations cause **MODY2** (Maturity Onset Diabetes of the Young) - mild hyperglycemia

---

## The Lineweaver-Burk Plot: Making Km Easy to Measure

### The Problem with Hyperbolic Curves
- Hard to determine exactly where Vmax is (asymptote)
- Therefore, hard to measure Km accurately

### The Solution: Double Reciprocal Plot

**Take reciprocals of the Michaelis-Menten equation:**

1/v₀ = (Km/Vmax) × (1/[S]) + 1/Vmax

**This is the equation of a straight line!** (y = mx + c)
![[Pasted image 20251016001340.png]]

**Reading the graph:**
- **Y-intercept** = 1/Vmax
- **X-intercept** = -1/Km  
- **Slope** = Km/Vmax

**Why this is better:**
- Straight line = easier to extrapolate
- Can measure Km and Vmax precisely from intercepts
- Can easily visualize effects of inhibitors

---

## Real Clinical Example: PHOSPHO1 Discovery

This enzyme story demonstrates **how enzyme kinetics are used in research medicine:**

**The Mystery:**
- Found in bone-forming cells (osteoblasts, chondrocytes)
- Amino acid sequence suggested it removes phosphate groups
- **But what was its natural substrate?**

**The Investigation (Substrate Screen):**
Tested various potential substrates:
- **Phosphoethanolamine (PEA)**: Km = 3.0 μM, Vmax = 4,120 nmol/min/mg
- **Phosphocholine (PCho)**: Km = 11.4 μM, Vmax = 3,600 nmol/min/mg

**The Conclusion:**
- PEA has lower Km (higher affinity) → likely the physiological substrate
- PHOSPHO1 reclassified as: **phosphoethanolamine/phosphocholine phosphatase**
- **Clinical relevance**: Involved in bone mineralization

**The lesson**: Enzyme kinetics aren't just theory - they're used to discover new biology and disease mechanisms!

---

## Enzyme Inhibitors: Drugs That Block Enzymes

**Most drugs work by inhibiting enzymes** - understanding the mechanism determines dosing!

### Types of Enzyme Inhibition
```
                    INHIBITORS
                        |
        _______________|_______________
        |                             |
   IRREVERSIBLE                  REVERSIBLE
        |                             |
        |                    _________|_________
        |                    |                 |
    (Covalent           COMPETITIVE      ALLOSTERIC
     binding)                            (Non-competitive
                                          & Mixed)
```

---

## 1. IRREVERSIBLE INHIBITION

### Mechanism
- Inhibitor forms a **covalent bond** with the enzyme
- **Permanent inactivation** - enzyme is destroyed
- Only way to restore activity: **synthesize new enzyme**
- **Effect on kinetics**: Reduces effective [enzyme], therefore reduces Vmax

**The Analogy**: Like supergluing a lock - the key will never work again

### Clinical Example 1: Aspirin (Acetylsalicylic Acid)

**Target enzyme**: Cyclooxygenase-1 (COX-1)

**Mechanism:**
1. COX-1 converts arachidonic acid → prostaglandin H2
2. Prostaglandins cause inflammation, pain, fever, platelet aggregation
3. Aspirin **acetylates a serine residue** near the active site
4. This physically blocks arachidonic acid from binding
5. COX-1 is permanently inactivated

**Clinical effects:**
- **Anti-inflammatory** (reduces prostaglandins)
- **Analgesic** (reduces pain)
- **Antipyretic** (reduces fever)
- **Antiplatelet** (prevents blood clots) - used for MI/stroke prevention

**Why low-dose aspirin works for clot prevention:**
- Platelets can't make new COX-1 (no nucleus)
- One dose of aspirin inactivates COX-1 for platelet's entire lifespan (7-10 days)
- 75mg daily is enough!

### Clinical Example 2: Organophosphates (Nerve Agents/Pesticides)

**Target enzyme**: Acetylcholinesterase (AChE)

**Normal function:**
- AChE breaks down acetylcholine (ACh) at nerve synapses
- ACh (neurotransmitter) → Choline + Acetate

**Mechanism of organophosphate poisoning:**
1. Organophosphate (e.g., DIPF, sarin, VX) binds to AChE
2. **Phosphorylates serine** in active site (irreversible)
3. AChE can't break down ACh
4. ACh accumulates at all nerve junctions

**Clinical effects (cholinergic crisis):**
- **SLUDGE** syndrome:
  - **S**alivation
  - **L**acrimation (tears)
  - **U**rination
  - **D**efecation
  - **G**I upset
  - **E**mesis (vomiting)
- Muscle twitching → paralysis
- Respiratory failure (diaphragm paralysis)
- **Can be fatal**

**Treatment:**
- **Atropine** (blocks ACh receptors - buys time)
- **Pralidoxime** (reactivates AChE if given early)
- Supportive care (ventilation)

---

## 2. COMPETITIVE INHIBITION

### Mechanism
**The inhibitor looks like the substrate** - it "tricks" the enzyme

**Key features:**
- Inhibitor binds to **active site** (same place as substrate)
- Substrate and inhibitor **compete** for binding
- Binding is **reversible**
- If you add enough substrate, you can outcompete the inhibitor

**The Analogy**: Like a fake key that fits in the lock but won't turn - but if you try enough real keys, eventually one will get in

### Effect on Kinetics

**Lineweaver-Burk Plot:**
![[Pasted image 20251016001423.png]]
**What changes:**
- **Km increases** (appears to - actually Km(apparent))
  - Need MORE substrate to reach Vmax/2
  - Makes sense: substrate has to outcompete inhibitor
- **Vmax unchanged**
  - At infinite [S], all inhibitor is displaced
  - Can still reach same maximum rate

**Memory trick**: **Competitive = Changeable Km** (but Vmax stays same)

### Clinical Example: Sulfonamide Antibiotics

**The bacterial target:** Dihydropteroate synthase (makes folic acid)

**Bacterial folic acid synthesis:**
- Bacteria MUST synthesize folic acid from **4-aminobenzoic acid (PABA)**
- Cannot use pre-made folic acid (unlike humans who get it from diet)
- Folic acid needed for DNA synthesis

**How sulfonamides work:**
- **Sulfonamides structurally mimic PABA**
- Competitively inhibit dihydropteroate synthase
- Bacteria starved of folic acid → can't make DNA → can't divide → die

**Chemical structures:**
```
PABA:          NH₂-⟨benzene⟩-COOH
Sulfonamide:   NH₂-⟨benzene⟩-SO₂-NHR
```
(Very similar structure - that's why it works!)

**Why it's selective:**
- Humans get folic acid from diet (leafy greens, fortified foods)
- We don't have the enzyme that uses PABA
- Sulfonamides don't affect human cells!

**Clinical uses:**
- UTIs (*E. coli*)
- *Pneumocystis jirovecii* pneumonia (in immunocompromised)
- Co-trimoxazole = sulfamethoxazole + trimethoprim (double hit on folate pathway)

**Resistance:**
- Bacteria can mutate enzyme so sulfonamide doesn't fit
- Or produce more PABA to outcompete drug

---

## 3. ALLOSTERIC INHIBITION (Non-Competitive & Mixed)

### Mechanism
**Inhibitor binds to a DIFFERENT site** (not the active site) - the "allosteric site"

**Key features:**
- From Greek: "allo" = other, "steric" = space
- Inhibitor and substrate can bind simultaneously
- Inhibitor causes **conformational change** in enzyme
- Reduces enzyme efficiency or substrate binding
- **Cannot be overcome by increasing [S]** - this is the key difference from competitive!

**The Analogy**: Like grabbing someone's wrist while they're trying to use a key - even if they have the key in the lock, they can't turn it properly

### Two Subtypes

**Non-Competitive Inhibition:**
- Inhibitor binds **independently** of substrate (doesn't care if substrate is bound)
- Reduces enzyme's **catalytic efficiency**
- **Effect on kinetics:**
  - **Vmax decreases** (enzyme works slower)
  - **Km unchanged** (substrate affinity not affected)

**Mixed Inhibition:**
- Inhibitor binding affects substrate binding (and vice versa)
- **Effect on kinetics:**
  - **Vmax decreases** (enzyme less efficient)
  - **Km increases** (substrate affinity also reduced)

### Lineweaver-Burk Plots

**Non-competitive:**
![[Pasted image 20251016001606.png]]
Lines intersect on x-axis (Km same, Vmax changes)

**Mixed:**
![[Pasted image 20251016001618.png]]

Both intercepts change (both Km and Vmax increase)

**Memory trick**: **Allosteric = Altered Vmax** (Km may or may not change)

### Clinical Example: Phosphofructokinase (PFK) - Feedback Inhibition

**The enzyme:** Phosphofructokinase (PFK)

- **Key regulatory enzyme in glycolysis**
- Catalyzes: Fructose-6-phosphate + ATP → Fructose-1,6-bisphosphate + ADP
- This is the **committed step** of glycolysis (point of no return)

**The regulatory mechanism:**

- PFK has **two ATP binding sites**:
    1. **Active site** (ATP is a substrate - donates phosphate)
    2. **Allosteric inhibitory site**

**How feedback inhibition works:**

- When ATP levels are **low** (cell needs energy):
    - Only active site occupied
    - Glycolysis proceeds normally
    - Makes more ATP
- When ATP levels are **high** (cell has plenty of energy):
    - Allosteric site also gets occupied
    - PFK changes shape
    - Fructose-6-phosphate can't bind well
    - Glycolysis slows down
    - Stops making unnecessary ATP

**The brilliant design:**

- **Product inhibition** - ATP inhibits its own production
- Prevents waste - why make energy you don't need?
- Elegant metabolic control

**Clinical relevance:**

- PFK deficiency (Tarui disease) - glycogen storage disease type VII
- Can't break down glucose for energy
- Muscle pain, exercise intolerance, hemolytic anemia

---

## Summary Table: Types of Inhibition

|Type|Binding Site|Reversible?|Effect on Vmax|Effect on Km|Can overcome with ↑[S]?|
|---|---|---|---|---|---|
|**Irreversible**|Active site (usually)|NO (covalent)|Decreases|No change|NO|
|**Competitive**|Active site|YES|No change|Increases|YES|
|**Non-competitive**|Allosteric site|YES|Decreases|No change|NO|
|**Mixed**|Allosteric site|YES|Decreases|Increases|NO|

---

## Clinical Case: Ethylene Glycol Poisoning (The "Aha!" Moment)

### The Scenario

**Emergency Room, 2 AM:**

- Man brought in by wife
- Found in garden shed
- Symptoms: Drunk-like (dizziness, confusion, slurred speech)
- Wife thinks he drank antifreeze instead of homemade wine
- **If untreated: acute kidney failure → death**

### The Biochemistry

**The poison:** Ethylene glycol (antifreeze)

- Not toxic itself!
- Metabolized by **alcohol dehydrogenase** (same enzyme that metabolizes ethanol)

**The toxic pathway:** Ethylene glycol → **Alcohol dehydrogenase** (+ NAD⁺) → Glycolaldehyde → Glycolic acid → Glyoxylic acid → **OXALATE**

**Why oxalate is deadly:**

- Forms calcium oxalate crystals in kidneys
- Crystals block renal tubules → acute kidney injury
- Also: metabolic acidosis, CNS depression

### The Treatment (Brilliant!)

**Administer a "near-intoxicating" dose of ETHANOL (or fomepizole)**

**Why this works - Competitive Inhibition!**

- **Ethanol competes with ethylene glycol** for alcohol dehydrogenase active site
- Both substrates look similar to the enzyme
- Ethanol has higher affinity (lower Km)
- If you give enough ethanol, it occupies most of the enzyme
- Ethylene glycol can't be metabolized → stays as non-toxic ethylene glycol
- **Ethylene glycol slowly excreted unchanged in urine**
- Crisis averted!

**Modern treatment:**

- **Fomepizole** (preferred) - specific alcohol dehydrogenase inhibitor, no inebriation
- Ethanol (if fomepizole unavailable)
- Hemodialysis (removes both poison and toxic metabolites)
- Supportive care

**The key insight**: Understanding competitive inhibition literally saves lives!

---

## Drug Examples: Enzyme Inhibitors in Medicine

### Quick Reference Table

|Condition|Target Enzyme|Drug (Inhibitor)|Type|
|---|---|---|---|
|**Bacterial infection**|Dihydrofolate reductase|Methotrexate|Competitive|
|**Fungal infection**|Squalene epoxidase|Terbinafine|Irreversible|
|**Viral infection**|Viral DNA polymerase|Acyclovir|Competitive|
|**Hypertension**|ACE (Angiotensin Converting Enzyme)|Captopril, enalapril|Competitive|
|**Heart attack/stroke prevention**|COX-1|Aspirin|Irreversible|
|**Inflammation/pain**|COX-1 & COX-2|NSAIDs (ibuprofen)|Competitive|
|**Gout**|Xanthine oxidase|Allopurinol|Competitive|
|**Peptic ulcer**|H⁺/K⁺-ATPase (proton pump)|Omeprazole (PPI)|Irreversible|
|**Depression**|Monoamine oxidase (MAO)|Tranylcypromine|Irreversible|

**Clinical pearl**: Knowing whether a drug is competitive or irreversible helps predict:

- **Dosing frequency** (irreversible = longer duration of action)
- **Drug interactions** (competitive inhibitors can be displaced)
- **Recovery time** (irreversible = need to make new enzyme)

---

## Key Concepts for Exams

### 1. **Km is about affinity**

- Low Km = high affinity = works at low [S]
- High Km = low affinity = needs high [S]
- Km is a **concentration** (units: M, mM, μM)

### 2. **Vmax is about capacity**

- Maximum rate when enzyme is saturated
- Depends on [enzyme] and how fast it works (turnover number)

### 3. **Initial velocity (v₀) is crucial**

- Only valid measurement
- Product concentration linear at start
- Substrate essentially constant

### 4. **Lineweaver-Burk makes everything linear**

- Easier to calculate Km and Vmax
- Easier to visualize inhibition patterns
- Y-intercept = 1/Vmax
- X-intercept = -1/Km

### 5. **Inhibition patterns**

- **Competitive**: Lines intersect on Y-axis (Vmax same, Km changes)
- **Non-competitive**: Lines intersect on X-axis (Km same, Vmax changes)
- **Irreversible**: Looks like non-competitive (Vmax decreases)

### 6. **Clinical applications**

- Enzyme levels diagnose disease (troponin, liver enzymes)
- Enzyme deficiencies cause inborn errors (PKU, G6PD deficiency)
- Most drugs are enzyme inhibitors
- Understanding mechanism predicts drug behavior

---
