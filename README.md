# PayPal JS SDK v6 Vanilla Demo

This version fixes the `no order ID provided` error.

The important v6 detail is:

```js
await paymentSession.start(
  { presentationMode: "auto" },
  createOrder()
);
```

`createOrder()` must resolve to:

```js
{ orderId: "PAYPAL_ORDER_ID" }
```

## Render

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
