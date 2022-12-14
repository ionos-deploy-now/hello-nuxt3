# Nuxt 3 Sample for Deploy Now

This is a basic Static Site Generation Nuxt website. You can use it as a starting point for your project or to give [Deploy Now](https://www.ionos.com/hosting/deploy-now) a try.

## How to deploy it 

1. [Sign in or sign up](https://ionos.space/sign-up) for Deploy Now
2. Click this button and name your new repo

   [![Deploy to IONOS](https://images.ionos.space/deploy-now-icons/deploy-to-ionos-btn.svg)](https://ionos.space/setup?repo=https://github.com/ionos-deploy-now/hello-nuxt3)

3. Deploy Now will detect necessary build dependencies and commands. You can adjust them and add environment variables.

Afterwards, Deploy Now will set up a [GitHub Actions](https://github.com/features/actions) workflow that will be triggered by every new code commit. Build results are automatically deployed to IONOS infrastructure. Projects go live under a preview URL, but you can replace it with a custom domain anytime.

## Helpful links
[Deploy Now docs](https://docs.ionos.space/)

[About Static Sites on Deploy Now](https://docs.ionos.space/docs/deploy-static-sites/)

[About build configuration](https://docs.ionos.space/docs/github-actions-customization/)

[Sign up for Deploy Now](https://ionos.space/sign-up)

Missing a feature? Create a [GitHub issue](https://github.com/ionos-deploy-now/ionos-deploy-now/issues). 

_IONOS Deploy Now - made with :heart: by [us](https://docs.ionos.space/about-us/) in Karlsruhe, Germany_

## Build Setup

Look at the [Nuxt 3 documentation](https://v3.nuxtjs.org) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
