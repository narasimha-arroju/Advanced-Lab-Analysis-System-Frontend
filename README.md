# Advanced-Lab-Analysis-System-Frontend
Next.js Frontend for Advanced-Lab-Analysis-System using Material-UI and Typescript.

# Next.js with TypeScript example

## How to use

Download the example [or clone the repo](https://github.com/mui-org/material-ui):

```sh
curl https://codeload.github.com/mui-org/material-ui/tar.gz/next | tar -xz --strip=2  material-ui-next/examples/nextjs-with-typescript
cd nextjs-with-typescript
```

Install it and run:

```sh
npm install
npm run dev
```

or:

[![Edit on CodeSandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/mui-org/material-ui/tree/master/examples/nextjs-with-typescript)

## The idea behind the example

[Next.js](https://github.com/zeit/next.js) is a framework for server-rendered React apps.

## Troubleshooting

### `Warning: Prop className did not match.`

If you get this warning, please make sure that you configure `getInitialProps` in `pages/_document.tsx` correctly. Check the code in this example for more details.
