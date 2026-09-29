# AquaBio Solutions LLP website

A responsive single-page company website draft based on the supplied company profile and the AquaBio aquaculture concept published in 2021. The design uses a water-inspired glass interface, the supplied red mark as a scalable SVG, an accessible light/dark theme toggle, and mobile navigation.

## Run locally

No build tools or package installation are required. Open `index.html` in a browser, or start a local web server in this folder:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Before publishing

Please confirm that the names, titles, product information, address, email addresses, phone number, and logo accurately reflect current company details. The aquaculture concept on the site is attributed to the company's 2021 post; its current product availability and treatment efficacy have not been independently verified.

Product descriptions are draft marketing content, not technical, medical, environmental, or regulatory claims. Confirm all product claims and application guidance with the company before relying on them.

## GitHub Pages

The `.github/workflows/pages.yml` workflow deploys the website after pushes to `dev` or `main`, or a manual workflow dispatch. Choose **GitHub Actions** under **Settings → Pages**. GitHub Pages websites are publicly accessible; private repository publishing requires an eligible GitHub plan.
