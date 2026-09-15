# Multicart

Multicart is an online shopping app. Shoppers can browse products by category, add items to a cart, and check out with card payments (via Stripe). Vendors can add and manage their own products. It also includes accounts (email/password and Google login), order history, and a support chat.

Built with Next.js, MongoDB, and Stripe.

## Running it locally

```bash
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000).

You'll need a `.env.local` file with your own database, auth, payment, and email credentials for it to work fully.
