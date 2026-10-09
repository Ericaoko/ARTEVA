# ARTÉVA

ARTÉVA is a responsive online art gallery concept for discovering fine-art photography prints. Visitors can browse a curated collection, search by title or category, filter by style, and add prints to a shopping bag before reviewing a demo checkout. The site also includes an editorial journal and a newsletter signup interface.

The experience is designed around a calm, gallery-inspired presentation that helps artwork take center stage across desktop and mobile screens.

## Features

- Responsive gallery landing page and print collection
- Search by print title or category
- Category filters for landscapes, abstract, architecture, coastal, portraits, and city work
- Shopping bag with item removal and subtotal
- Checkout summary with shipping calculation
- Editorial journal with article detail views
- Newsletter signup interface

## Technology

- React 18
- TypeScript
- Vite
- CSS

## Getting started

### Requirements

- Node.js and npm

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Vite will print the local URL in the terminal.

### Create a production build

```bash
npm run build
```

### Preview the production build

```bash
npm run preview
```

## Project structure

```text
src/
  App.tsx           Main gallery, collection, and shopping bag
  App.css           Application styles
  CheckoutPage.tsx  Checkout and order summary interface
  JournalPage.tsx   Journal listing and story details
  main.tsx          React application entry point
```

## Demo status

This is a front-end demo, not a live storefront. Products are sample data, the bag is held in memory and is cleared on refresh, and checkout displays a success screen without processing a payment or creating an order. The newsletter form is also a local interface only.

Before accepting real orders, replace the sample product data and images with approved content, connect a payment provider using its secure hosted or tokenized flow, and implement server-side order creation and confirmation. Do not collect or store raw card details in this client-side application.
