# Fancie's World
Static site for GitHub Pages (`www.fanciesworld.com`). No build step. `CNAME` is included; DNS must be set at your registrar.

All editable content lives in `js/site-config.js`.
- **Add a song:** upload the MP3 to `audio/` (only files you have rights to), then set `audioUrl:"audio/name.mp3"`, `available:true` (optional `coverArt`, `description`).
- **Products / beauty / books / journal / videos:** add an object to the matching array (shapes are in the comments). Empty arrays show "Coming Soon".
- **Shopify:** set `shopifyUrl` and category `url`s. Connect Printify to Shopify inside Shopify; never put API keys in this repo.
- **Newsletter:** set `newsletterEndpoint` to a real POST endpoint; success shows only on a 2xx reply.
- **Amazon:** set `affiliateDisclosure` only if you are in Amazon Associates.
- **Hero:** replace `images/fancies-world-hero.png`.
