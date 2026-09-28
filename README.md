# AquaBio Solutions LLP website

A responsive, single-page website for AquaBio Solutions LLP, based on the supplied company profile. The standalone `index.html` includes inline styles and scripts for responsive layout, mobile navigation, and a visitor-selectable dark or light theme. The theme follows the visitor's device preference initially and remembers a manual choice in the browser.

## Preview locally

No build tools or package installation are required. Open `index.html` in a browser, or serve the repository root with a static web server.

## Review before launch

Confirm names, titles, product language, address, email addresses, and phone number against current company information. The phone and email details are from the supplied company profile. Descriptive and product language is draft marketing copy, not technical or regulatory claims.

## GitHub Pages

The GitHub Actions workflow in `.github/workflows/pages.yml` deploys the static site after pushes to `main` and can also be started manually. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source. GitHub Pages websites are publicly accessible. Publishing from a private repository requires an eligible GitHub plan; on the free plan, make the repository public before enabling Pages.
