# JimeBlue Boilerplate - Basic

Welcome to the JimeBlue Boilerplate - Basic, a streamlined and efficient starter template for building client-side rendered (CSR) applications with Nuxt 3. This boilerplate is designed with simplicity in mind, featuring powerful tools that accelerate your development workflow.

## Features

- **Nuxt 3**: Built with the latest Nuxt framework, leveraging the power of the Composition API.
- **Client-Side Rendering (CSR)**: Optimized for front-end rendering, ensuring a fast and dynamic user experience.
- **Nuxt UI**: Integrated with Nuxt UI for beautiful, ready-to-use components.
- **Tailwind CSS**: Styled with Tailwind CSS for modern, utility-first design.
- **Nuxt HeadlessUI Dialog**: Includes a dialog component using Nuxt HeadlessUI for accessible UI elements.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 16.x or later)
- [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)

### Installation

Clone this repository and install dependencies:

Make sure to install the dependencies:

```bash
git clone https://your-repo-url.git
cd jimeblue-boilerplate-basic
yarn install

# or
npm install
```

## Running the Development Server

To start the development server, run:

```bash
yarn dev

# or

npm run dev
```

The app will be available at `http://localhost:3000.`

## Building for Production

To build the project for production:

```bash
yarn build
# or
npm run build

```

The production-ready files will be in the .output folder.

## Customization

### Nuxt HeadlessUI Dialog

This boilerplate includes a modal/dialog component using Nuxt HeadlessUI. To customize the dialog, you can find the component in the components/ folder.

### Tailwind CSS

Tailwind is already configured in the project. You can modify the tailwind.config.js to adjust theme settings, breakpoints, and more.

### Nuxt UI

Nuxt UI is already configured in the project. You can modify the app.config.ts to customize the look and feel of the components at runtime with HMR. Check out the [Nuxt UI docs](https://ui.nuxt.com/getting-started/theming)
