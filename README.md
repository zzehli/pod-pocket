# Pod Pocket: WIP Podcast Feed
## Run dev env
* Frontend: `npm run dev`

## Dev Plan:
Week One: Aug 7 - 13
- [ ] frontend setup: Vite, DaisyUI, react-router
- [ ] feeds page, common header component
- [ ] backend setup: nestJS, prisma
- [ ] basic RSS fetch and routes to get feeds
Week Two: Aug 14 - 21
- [ ] Azure account management
- [ ] JWT
Week Three: Aug 22 - 27
- [ ] Individual podcast page
- [ ] RSS subscription

## Vite: Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
