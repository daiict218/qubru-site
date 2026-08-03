# qubru-site

Marketing landing page for **Qubru** — AI-native compliance & records intelligence for insurance carriers.

Static marketing site with no build step. `index.html` is the landing page; `demo.html` contains the demo-request form and `privacy.html` contains the privacy policy. Brand tokens (pink `#EC136E`, navy `#201C50`, Work Sans) are carried from the product frontend.

The demo form posts to Formspree and displays an inline success state without leaving the site. The product CTA links to the QA application at `https://qa.qubru.com/`.

## Hosting
Served via **GitHub Pages** from `main` (root). Custom domain `qubru.com` is set via the `CNAME` file + DNS records at the registrar (Network Solutions).
