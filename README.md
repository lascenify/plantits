# Gatsby Starter eCommerce

Pot shop created based on the [GatsbyJS](https://www.gatsbyjs.org/)
[starter](https://github.com/parmsang/gatsby-starter-ecommerce) for creating an
eCommerce site.

## Getting started

Clone the project

`git clone https://github.com/lascenify/plantits`

Install dependencies

`npm i`

### Running in development

`npm run develop`

### Additional Setup

Both a moltin and Stripe account are needed for this store to run successfully.

Create a `.env.development` and `.env.production` file at the project root with
your moltin `client_id` and Stripe test `publishable key`.

```dosini
MOLTIN_CLIENT_ID=
STRIPE_PUBLISHABLE_KEY=
```

## Features

- Moltin eCommerce API
- React 16
- PWA (includes manifest.webmanifest & offline support)
- Eslint & Prettier
- Styled Components
- Google Analytics - (you enter the tracking-id)
- Semantic-UI
- Authentication via Moltin (Login and Register)
- Stripe checkout
