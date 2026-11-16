# aatm · legal

Public policy pages for the aatm app (`ai.aatm.app`), served by GitHub Pages.

- `privacy/index.html` — no longer the policy. Since #50 (aatm-website) it only sends people to
  `https://aatm.ai/privacy/`, which carries the current policy. The 4 October text is removed.
- `delete-account/index.html` — Account deletion, the public URL Play requires
  alongside the in-app path.
- `support/index.html` — Support page, the App Store Support URL.
- `style.css` — shared by all pages so they cannot drift.

Published from `main` at the repository root. To move these to `aatm.ai`,
add a `CNAME` file containing the domain and point a DNS record at
`aatmai.github.io`; the paths stay the same.
