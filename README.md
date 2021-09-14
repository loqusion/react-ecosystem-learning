# React Ecosystem Learning

## General Tips

- View projects on GitHub for inspiration - e.g. packages, code style, configuration, project structure
  - Some of my favorites: [MUI](https://github.com/mui-org/material-ui), [Storybook Design System](https://github.com/storybookjs/design-system), [Storybook Frontpage](https://github.com/storybookjs/frontpage), [NextJS](https://github.com/vercel/next.js/), [useSWR](https://github.com/vercel/swr)

## Fundamentals

### Web Technology

[Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web)

> w3schools will often appear at the top of search engine results, instead of MDN. To block it, you can install an extension like [uBlacklist](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe).

[web.dev](https://web.dev/)

### JavaScript

[You Don't Know JS](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/README.md)

[MDN JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

### React

[React Main Concepts](https://reactjs.org/docs/hello-world.html)

[React Hooks](https://reactjs.org/docs/hooks-intro.html)

[Dan Abaramov's blog](https://overreacted.io/)

- Esp. [A Complete Guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/)

### TypeScript

[TypeScript Docs](https://www.typescriptlang.org/docs)

[React TypeScript Cheatsheet](https://react-typescript-cheatsheet.netlify.app/docs/basic/setup)

### Package Management

[NPM](https://docs.npmjs.com/about-npm)

[Yarn](https://yarnpkg.com/)

## NextJS/Vercel

### [NextJS Docs](https://nextjs.org/docs/getting-started)

> Next.js gives you the best developer experience with all the features you need for production: hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more. No config needed.

### [SWR](https://swr.vercel.app/)

> The name “SWR” is derived from stale-while-revalidate, a HTTP cache invalidation strategy popularized by [HTTP RFC 5861](https://tools.ietf.org/html/rfc5861). SWR is a strategy to first return the data from cache (stale), then send the fetch request (revalidate), and finally come with the up-to-date data.

## Component Libraries

Component libraries consist of common reusable UI components that serve as the backbone of a UI. Using a component library makes development faster and easier by isolating components, and it ensures a consistent user experience.

[Storybook](https://storybook.js.org/) is a popular tool used to create design systems. It also helps you document components and automatically visually test your components to prevent bugs.

### Popular UI Frameworks

[Material UI](https://material-ui.com/)

[Ant Design](https://ant.design/)

[Chakra UI](https://chakra-ui.com/)

[Tailwind UI](https://tailwindui.com/)

[Semantic UI](https://semantic-ui.com/)

[Carbon Design](https://www.carbondesignsystem.com/)

[Polaris by Shopify](https://polaris.shopify.com/)

[React Bootstrap](https://react-bootstrap.github.io/)

### UI Design Guidelines

[Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)

[Material Design](https://material.io/design)

## Popular Packages

[Styled Components](https://styled-components.com/)

[Formik](https://formik.org/)

[Axios](https://github.com/axios/axios)

[Redux](https://redux.js.org/) (make sure to read [this](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367) first!)

[React Window](https://github.com/bvaughn/react-window)

## Dev Tools

[Editorconfig](https://editorconfig.org/)

[ESLint](https://eslint.org/)

[Stylelint](https://stylelint.io/)

[Prettier](https://prettier.io/)

[Husky](https://github.com/typicode/husky)

[Lint-Staged](https://github.com/okonet/lint-staged)

## Monorepo Workflow

Monorepos are used to contain multiple related packages. For instance, a full-stack application could have a backend `api` package and frontend `web` and `mobile` packages, with shared assets, tools, constants, etc. in a `common` package. See [Babel's monorepo.md](https://github.com/nicolo-ribaudo/babel/blob/7c332835fed6ff975d2cffcba5f83490a5704383/doc/design/monorepo.md) for more discussion on monorepos.

### Monorepo Tools

[Yarn Workspaces](https://classic.yarnpkg.com/en/docs/workspaces/)

[Lerna](https://lerna.js.org/)

[Nx](https://nx.dev/)

## Mocking

[MirageJS](https://miragejs.com/)

[Postman](https://www.postman.com/)

## Deep-Dive

You usually won't have to work directly with these, but it helps to know they exist and how they convert your code into assets used in actual production, especially for performance reasons. Knowing some basic configuration options can also be useful.

### Code Transpilation/Bundling

[Webpack](https://webpack.js.org/)

[Babel](https://babeljs.io/)

## Things to look into for the future

### Testing

[React Testing Overview](https://reactjs.org/docs/testing.html)

[Jest](https://jestjs.io/)

[React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

- Alternative: [Enzyme](https://enzymejs.github.io/enzyme/#)

[Fullstory](https://www.fullstory.com/)

### Universal React Applications

[Expo](https://expo.io/)

### Modern Architecture

[Remix](https://remix.run/)

## Misc. Resources

[Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap) (this is where I started)

[Jamstack](https://jamstack.org/)

[CSS Tricks](https://css-tricks.com/)

[Modern Web Engineering & Micro Frontends](https://www.ivaylopavlov.com/modern-web-engineering-micro-frontends/)

[React Libraries in 2020](https://www.robinwieruch.de/react-libraries)

[Joel on Software](https://www.joelonsoftware.com/)

[Josh Comeau](https://www.joshwcomeau.com/)
