# PayPal JS SDK v6 Vanilla JS Demo

This project follows the vanilla JS SDK v6 approach from:

https://docs.paypal.ai/developer/how-to/sdk/js/v6/configuration

Features:

- Vanilla JS implementation
- Direct `window.paypal.createInstance()`
- JS SDK v6 loaded from CDN
- Express server for Orders API
- Server-side order creation
- Server-side capture
- Render deployment ready

## Render Settings

Build Command:

```bash
yarn install
```

Start Command:

```bash
yarn start
```

Environment Variables:

```bash
NODE_VERSION=20
PAYPAL_ENV=sandbox
PAYPAL_SANDBOX_CLIENT_ID=YOUR_SANDBOX_CLIENT_ID
PAYPAL_SANDBOX_CLIENT_SECRET=YOUR_SANDBOX_CLIENT_SECRET
```
