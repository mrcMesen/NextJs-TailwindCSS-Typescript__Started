# Started Project - Next JS + Tailwind CSS with Typescript

Base project to start coding a Next Js App with Tailwind CSS
Using `Typescript - eslint - prettier - husky pre commit with lint-staged`

### Initial Structure

```
-public              ~ Images and others assets
-src
---components        ~ Components for app
---hooks             ~ Custom Hooks Here
---pages             ~ Sreens for APP
-----api             ~ API next js
---styles            ~ Global CSS stylea
```

#### Path Alias

When importing you can use `@components/` to refer to `src/components/*` this is to avoid the path hell `../../../components`.

Another Path Alias configurated:
`@pages/`
`@hooks/`

Edith the file `jsconfig.json` to add more paths alias.

#### Dependecies

```bash
"dependencies": {
  "autoprefixer": "^10.2.4",
  "next": "10.0.6",
  "postcss": "^8.2.5",
  "react": "17.0.1",
  "react-dom": "17.0.1",
  "tailwindcss": "^2.0.3"
},
"devDependencies": {
  "@types/node": "^14.14.25",
  "@types/react": "^17.0.1",
  "@typescript-eslint/eslint-plugin": "^4.14.2",
  "@typescript-eslint/parser": "^4.14.2",
  "eslint": "^7.19.0",
  "eslint-config-prettier": "^7.2.0",
  "eslint-plugin-jsx-a11y": "^6.4.1",
  "eslint-plugin-prettier": "^3.3.1",
  "eslint-plugin-react": "^7.22.0",
  "eslint-plugin-react-hooks": "^4.2.0",
  "husky": "^4.3.8",
  "lint-staged": "^10.5.4",
  "prettier": "^2.2.1",
  "typescript": "^4.1.3"
},
```

## Getting Started

- Download the project
- Change the project name in package.json
- Install and Run the development server:

```bash
yarn install
yarn dev
```

- Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Learn More

#### To learn more about Next.js

Take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

#### To learn more about Tailwind

- [Tailwind Documentation](https://tailwindcss.com/docs)

#### To learn more about Typescript

- [Typescript Documentation](https://www.typescriptlang.org/)

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
