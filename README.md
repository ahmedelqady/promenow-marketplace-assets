# promenow-marketplace-assets

Public marketplace assets for [ProMeNow](https://promenow.app) digital products — cover images, thumbnails, and other buyer-facing graphics referenced by external commerce platforms (Gumroad, Etsy, Payhip).

## Why public

Gumroad's `/v2/products/:id/covers` endpoint requires a publicly fetchable URL. Hosting these assets in a public repo lets Gumroad's backend rehost them onto `public-files.gumroad.com` at cover-attach time. Same shape works for any platform that accepts a URL-based cover/preview field.

## Contents

| Path | Purpose |
|---|---|
| `covers/<slug>-compA-gumroad-cover-1280x800.png` | Gumroad cover (1280×800, lifestyle composition A from the Higgsfield mockup pass) for the CareerFit Premium Workplace Kits. Auto-attached at publish time by `gumroad-publish.py` in the `_ProMe` repo. |

## Source

These PNGs are generated and curated in the private [`_ProMe`](https://github.com/ahmedelqady/_ProMe) repo at `business/portfolio/digital-products/careerfit/v2-factory/04_Listings/mockups/derived/`. This repo is the publish surface — content here is downstream of source-of-truth.

## License

MIT — these are buyer-facing marketing images for ProMeNow's own products. Reuse permitted but the underlying product branding is reserved.
