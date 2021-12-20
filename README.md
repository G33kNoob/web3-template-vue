# Vue 3 + Typescript + Vite

This template should help get you started developing a web3.0 application with Vue.js, TailwindCSS and Typescript. This is a work in progress project and I'll be adding new features.

## Features

This projects includes multiple features out of the box including:

- Metamask wallet integration: there is a "Connect Wallet" button that triggers Metamask authorization
- State management with Pinia: the metamask wallet account info is kept in a store. That way, it can be accessed from multiple views and components.

- TailwindCSS integration
- Vue router

## To-Do:

- [ ] Disconnect wallet
- [ ] Identify if connected blockchain is the correct one.
- [ ] Support for multiple accounts instead of just one
- [ ] Support for other wallets

### How I built this project step-by-step

Created new Vite project with `npm init vite@latest web3-template-vue `

Installed all dependenciess

Installed TailwindCSS following the official guide https://tailwindcss.com/docs/guides/vite

Installed Pinia and created a basic wallet store

Installed vue-router (v4) and created a couple of views

Created a NAvBar component with the buttons to connect Metamask wallet, save wallet info in store and navigate between routes

Installed node types to use `process.env` with `npm install @types/node --save-dev`

Fixed @ imports in `vite.config.js`