# aatm · legal

Public policy pages for the aatm app (`ai.aatm.app`), served by GitHub Pages.

- `privacy/index.html` — Privacy Policy, referenced by the Google Play listing.
- `delete-account/index.html` — Account deletion, the public URL Play requires
  alongside the in-app path.
- `style.css` — shared by both pages so they cannot drift.

Published from `main` at the repository root. To move these to `aatm.ai`,
add a `CNAME` file containing the domain and point a DNS record at
`aatmai.github.io`; the paths stay the same.
