# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

# TapOnIt FrontEnd - Assignment

Web Application of TapOnIt Assignment

## Prerequisite

To build and run the project following cli is necessary

- [Vue](https://vuejs.org/guide/introduction.html)
- [Nuxt](https://v2.nuxt.com/docs/get-started/installation)

## Setup

Make sure to install the dependencies:

```bash
# npm
npm install --legacy-peer-deps

# yarn
yarn install --legacy-peer-deps
```

## Login Credential

```
email: Email saved in Student table (e.g taponit@gmail.com)
password: TapOnIt@123
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm run dev

# yarn
yarn dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm run build

# yarn
yarn build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm run preview

# yarn
yarn preview
```

## dependencies

```
"axios": "^1.4.0"
```

## devDependencies

```
"@nuxt/devtools": "latest",
"@nuxtjs/tailwindcss": "^6.8.0",
"@types/node": "^18",
"axios-mock-adapter": "^1.21.5",
"nuxt": "^3.5.2"
```

## Folder Structure

- api &gt; `Contains mock api and axios config`

- assets &gt; `Contains tailwind css`

- components &gt; `Contains all the reusable components`

- pages &gt; `Contains all the screens`

- public &gt; `Contains the build files`

- utils &gt; `Contains all helper functions`

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
