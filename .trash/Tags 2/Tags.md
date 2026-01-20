`// All tags sort by name
const allTags = Object.keys(app.metadataCache.getTags())
  .sort((a, b) => a.localeCompare(b))

dv.header(2, "All Tags")

// Display tags as a list
let content = ''
for (const tag of allTags) {
  content += `- ${tag}\n`
}
dv.el('div', content)
`