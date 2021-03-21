# React Ecosystem Learning

## General Tips

- View projects on GitHub for inspiration - e.g. packages, code style, configuration, project structure
  - Some of my favorites: [useSWR](https://github.com/vercel/swr), [Storybook Design System](https://github.com/storybookjs/design-system), [Storybook Frontpage](https://github.com/storybookjs/frontpage), [Carbon Design System](https://github.com/carbon-design-system/carbon), [Angular](https://github.com/angular/angular), [NextJS](https://github.com/vercel/next.js/)

## Fundamentals

### Web Technology

[Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web)

> Don't use w3schools. MDN is better in every way. If it appears in the top of your search results (which it likely will), I recommend installing an extension like [uBlacklist](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe) and blocking it so that it doesn't take up space.

[web.dev](https://web.dev/)

### JavaScript

[You Don't Know JS](https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/README.md)

[MDN JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

### React

[React Main Concepts](https://reactjs.org/docs/hello-world.html)

> The React tutorials use class components, but functional components with hooks are preferred. There isn't much reason to use class components over functional components any more, besides when optimizations are needed that can't be implemented with hooks (e.g. `shouldComponentUpdate`).

[React Hooks](https://reactjs.org/docs/hooks-intro.html)

[Dan Abaramov's blog](https://overreacted.io/)

- Esp. [A Complete Guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/)

### TypeScript

[TypeScript Docs](https://www.typescriptlang.org/docs)

[React TypeScript Cheatsheet](https://react-typescript-cheatsheet.netlify.app/docs/basic/setup)

### Package Management

[NPM](https://docs.npmjs.com/about-npm)

[Yarn](https://yarnpkg.com/)

> I mostly use Yarn 1, but migrating to Yarn 2 is something to look into for projects not using React Native ([it's incompatible with Yarn 2's PnP](https://yarnpkg.com/features/pnp#incompatible)).

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

These tools help ensure code quality and consistency. A must for every codebase that will grow to a significant size over time, for maintainability reasons.

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

Using a mock server instead of a real backend allows you to develop the frontend independently from the backend. This saves development time and makes debugging easier by reducing the span of potentially faulty code to just the frontend. It also just streamlines the DX (Developer eXperience) overall imo.

[Postman](https://www.postman.com/)

[MirageJS](https://miragejs.com/) (I haven't personally used it but it looks like a great alternative to Postman)

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
