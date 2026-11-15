# HWD Media — EN

Static website at https://hwdmedia.com/, published by GitHub Pages from
`master` at the repository root. No installation or build command is required.

- `index.html`: company homepage, team and contact details.
- `boomstream.html`: localized product overview, capabilities, use cases and integration resources.
- `assets/site.css`: shared responsive layout and light/dark themes.
- `assets/product.css`: styling scoped to the product page.
- `assets/theme-init.js` and `assets/site.js`: theme preferences, language links,
  optional photo dialogs and the official Boomstream embed.
- `assets/team/`: supplied original team portraits.
- `CNAME`: custom domain; preserve it when editing the website.

The player uses Boomstream iframe SDK 1.5.0, automatic site theme matching and
`config.jsonp?title=0`. The product page and homepage keep the same localized video.
Language links on the product page point to its counterpart on the other domain.

Product descriptions are based on the official localized sources:

- https://boomstream.com/
- https://boomstream.com/online-video-platform
- https://boomstream.com/live-broadcasting
- https://boomstream.com/video-protection
- https://boomstream.com/pay-per-view
- https://boomstream.com/meet
- https://boomstream.com/documentation/api

Before merging, check local links and assets, canonical/hreflang URLs, JavaScript
syntax, light/dark themes and responsive layouts. Also verify homepage navigation,
photo dialogs and the player when changing shared JavaScript.
