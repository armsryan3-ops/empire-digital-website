# Empire Digital

A responsive agency website built with HTML, CSS, and JavaScript. No build step or npm dependencies are required.

## Development

From `/workspace/empire-digital-website`, run:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

The server serves the website on port 3000. Stop it with Ctrl+C.

## Before launch

- Replace `hello@empiredigital.example` in `index.html` with your real contact address and remove the placeholder notice.
- Review the Google Ads and Google Business Profile service descriptions.
- Add verified qualifications or case studies when available.
- Review agency copy and branding.
- Google Fonts are optional external resources; system fonts provide a fallback.

## Validation

```sh
node --check script.js
curl --fail http://127.0.0.1:3000/
```

Check mobile navigation, keyboard navigation, and section links in a browser. No form submissions or analytics are collected by this site.
