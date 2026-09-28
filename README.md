# AquaBio Solutions LLP website

A responsive, single-page website for AquaBio Solutions LLP, based on the supplied company profile. It includes the applied-bioscience overview, 12 business segments, product families, reverse-engineering process, founders, contact details, and a visitor-selectable dark or light theme. The selected theme is remembered in the browser; the initial theme follows the device preference.

## Preview locally

No build tools or package installation are required. Open `index.html` in a browser, or serve the repository root with a static web server.

## Review before launch

Confirm names, titles, product language, address, email addresses, and phone number against current company information. The phone and email details are from the supplied company profile. Descriptive and product language is draft marketing copy, not technical or regulatory claims.

## GitHub Pages

A GitHub Actions workflow in `.github/workflows/pages.yml` deploys the static site after pushes to `main` and can also be started manually. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source. If Pages cannot be enabled on this private repository, the GitHub account or organization plan does not support private Pages for it. The repository can remain private with an eligible plan; making it public would let anyone browse the repository and site.
