# Ringbase website

Ringbase’s public brand website. Built with React, TypeScript and Vinext; exported as static files for Vercel. It presents the working iOS prototype and clearly labels planned subscriptions, enterprise features, open-source release and platform expansion.

## Development

Requires Node.js 22.13 or later (Node 24 recommended).

```sh
npm ci
npm run dev
```

Use the local URL printed by the development server. The illustrative call card has accessible keyboard-controlled tabs and editable session-only notes. No call is placed, data sent, or subscription purchased by the demo.

## Checks and deployment

```sh
npm run lint
npx tsc --noEmit
npm run build
```

Vercel reads `vercel.json`: framework Other, build `npm run build`, static output `dist/client`. Connect the main branch of this repository for automatic production deployments. No environment variables or provider API keys are required.

## Content and assets

- App subscriptions and number provisioning are roadmap features, not available for purchase here.
- The Ringbase icon is authored vector geometry in `public/icon.svg`.
- The blue glass-loop image was generated for Ringbase and optimised to WebP.
- Fonts use the starter’s Geist family configuration.
- No tracking scripts, analytics, contact collection or advertising pixels are included.
- Product contact links can be added once a verified contact address is supplied.

The app’s source release is planned separately; this repository contains only the website.
