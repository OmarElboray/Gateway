# Gateway

Gateway is a static landing page for a school research and mentorship platform. It presents the product, its goals, and an access-request flow for schools that want to build a stronger research culture.

## Highlights

- Student research and project opportunities.
- Mentorship and feedback workflows.
- School-facing messaging and access requests.
- Responsive, single-page presentation with custom visual branding.

## Run locally

Gateway has no build step or runtime dependency. Clone the repository and serve it with any static file server:

```bash
git clone https://github.com/OmarElboray/Gateway.git
cd Gateway
python -m http.server 8000
```

Open <http://localhost:8000>.

Opening `index.html` directly also works for basic previewing, but a local server is recommended for consistent browser behavior.

## Files

```text
Gateway/
├── index.html       # Landing page
├── thanks.html      # Request confirmation page
├── gateway-logo.svg # Wordmark
├── gateway-icon.svg # Favicon
├── og-image.png     # Social preview image
├── robots.txt
└── sitemap.xml
```

## Customization

Most page content and styling lives in `index.html`. Update links, copy, and the request form destination there before deploying.
