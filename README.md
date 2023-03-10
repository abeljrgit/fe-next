# Front-end Boilerplate

Front-end boilerplate using Next.JS, SWR, React.JS, Tailwind CSS, TW-Elements and Typescript.

## Features

- Next.JS for rendering the app on the server side.
- React.js library for web app development.
- Jest for unit testing.
- Typescript for type safety and scalability.
- Tailwind CSS for fast styling.
- TW-Elements for quick UI.

## Run Locally

Download the repository

Go to the project directory

Install dependencies(npm):

```bash
  npm install
```

Start the next.js development server(npm):

```bash
  npm run dev
```

Build your work(npm, production purpose, target ES6):

```bash
  npm run build
```

Start your build files(npm, production purpose):

```bash
  npm run start
```

Export your files(npm, production purpose, spa):

- Please take note that you cannot use ISG, SSG and some Next.JS functionality. Kindly refer to the [documentation](https://nextjs.org/docs/advanced-features/static-html-export)

```bash
  npm run export
```

## Folder Structure

Folder name is self explanatory

    src
    ├── .next - dev or build files, git ignored
    ├── node_modules - git ignored
    ├── out - export files, git ignored
    ├── public
    └── src
        ├── assets
        ├── components
        ├── context
        ├── hooks
        ├── pages
        |   └── api - internal api
        ├── services - external api
        ├── styles
        └── types

## Documentation

[Next.JS](https://nextjs.org/docs/getting-started)  
[NextAuth.JS](https://next-auth.js.org/getting-started/introduction)  
[React.JS](https://reactjs.org/docs/getting-started.html)  
[Jest](https://jestjs.io/docs/getting-started)  
[Tailwind CSS](https://tailwindcss.com/docs/)  
[Typescript](https://www.typescriptlang.org/docs/)

## Authors

- [@abeljrgit](https://github.com/abeljrgit)
