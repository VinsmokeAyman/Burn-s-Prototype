# Burn’s — US Smash Burger

React + Vite restaurant frontend using supplied Burn’s photography.

## Run

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
npm run preview
```

## Pages

- Home: brand introduction, signature products, club and kitchen story
- Menu: category filters, product pricing and add-to-cart
- Special offers: student lunch menu
- Fidelity: loyalty card preview and inactive-program notice
- Profile: local browser demo profile
- Order: cart quantities, totals, empty state and demo confirmation

Routes use URL hashes and work on static hosting. Prices are transcribed from the supplied menu image. Product photos are illustrative; restaurant approval is needed to map each photo to its exact dish and confirm current prices, availability and allergens.

## Integration status

This is a frontend demonstration. No real orders, payments, accounts or loyalty rewards are processed. Profiles stay in localStorage on the current browser; the cart is held in memory for the session. Connect a restaurant backend, approved loyalty rules and payment provider before accepting real orders.

Production build was verified. The private Sites project was registered, but publication could not complete because the installed Sites package is missing its required site-workflow.mjs helper. The local Vite preview remains available.
