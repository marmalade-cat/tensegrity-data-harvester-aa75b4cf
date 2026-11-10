# tensegrity-data-harvester

Purpose: record and assemble machine-readable datasets (CSV/JSON) referenced by a Nature article and africavernaculararchitecture.com link. This prototype provides instructions, example commands to fetch files, and simple validation/log templates.

What I included
- index.html: a compact interactive guide with copyable shell commands and validation examples.
- README: this file.

How to use
1. Open index.html in a browser for instructions and example curl/wget commands.
2. Fetch candidate URLs found in the two source pages (inspect page HTML, follow data links). Save files into a local folder named "raw".
3. Use the provided validation commands (csvkit and jq examples) or the included lightweight checks in index.html.

Notes on provenance
- This repo does not fetch content automatically. Web excerpts and page content are untrusted; you must inspect the Nature article and africavernaculararchitecture.com link to locate dataset URLs. Record each raw file's source URL and date when you download it.

Limitations
- Prototype does not include downloaded datasets. That keeps the repo small and public. Use the templates here to gather data and add files to the repository manually.

License: CC0
