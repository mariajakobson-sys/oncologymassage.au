# Oncology Massage Australia

A calm, single-page informational website for **oncologymassage.au**, with a link to **Sacred Layers**. The design uses a light green-blue palette, airy spacing, and an original flowing dandelion illustration to reflect gentle, adapted touch.

## Edit locally

- `dist/index.html` — page content, questions, and links
- `dist/styles.css` — colours, typography, and responsive layout
- `dist/assets/` — original artwork and favicon

The website has no third-party dependencies, tracking, forms, or external font requests.

## Preview

For a quick preview, open `dist/index.html` in your web browser. The artwork and styling also work directly from the saved files.

With Node.js installed, run:

```text
node scripts/preview.mjs
```

Open **http://127.0.0.1:4173**. Refresh after editing a file. Stop the server with Ctrl+C. You can also use `npm run dev` when npm is installed.

## Netlify

When ready to publish, import this GitHub repository in Netlify. The included `netlify.toml` specifies:

- Publish directory: `dist`
- Build command: leave empty

No build step or dependency installation is required. Only the `dist` folder is published. See [Netlify's build configuration guide](https://docs.netlify.com/build/configure-builds/overview/).

Add `oncologymassage.au` as a custom domain in Netlify after the initial deploy. Use the exact DNS records Netlify displays when connecting it through GoDaddy. Keep existing email-related records. The domain and hosting are not configured by creating these files.

## Content references

Medical information was checked on 14 October 2026 against:

- [Cancer Council NSW — Massage](https://www.cancercouncil.com.au/cancer-information/living-well/complementary-therapies/individual-therapies/massage/)
- [Cancer Council Australia — Does massage spread cancer?](https://www.cancer.org.au/iheard/does-massage-spread-cancer)
- [Cancer Australia — Complementary therapies](https://www.canceraustralia.gov.au/impacted-cancer/treatment/complementary-therapies)

The page offers general information and directs visitors to their cancer care team for individual advice. It makes no claim that massage treats cancer. No practitioner qualifications, testimonials, prices, or booking availability are assumed. Review the copy and service links before publishing, and review health information periodically.

## Current stage

The single-page website is ready for deployment from this repository. Import it in Netlify to publish the `dist` folder, then configure the custom domain through Netlify and GoDaddy.
