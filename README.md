### web: https://video-calling-hp.vercel.app/


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json', './tsconfig.app.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list


Preview:--

![Screenshot 2024-07-30 174801](https://github.com/user-attachments/assets/4c648195-08bc-4d6f-bcc7-b5e5143c45f9)

![Screenshot 2024-07-30 174817](https://github.com/user-attachments/assets/d5e4816a-1d22-420f-b8ca-fd7751a4a517)

![Screenshot 2024-07-30 174831](https://github.com/user-attachments/assets/81b60647-fd5e-4d06-ace7-5c96820004a9)

![Screenshot 2024-07-30 174848](https://github.com/user-attachments/assets/c822d027-9ed9-46a4-8bcf-9bb86197f29a)

![Screenshot 2024-07-30 174928](https://github.com/user-attachments/assets/3f8834be-6f73-405c-8844-35259e5fa5bc)

![Screenshot 2024-07-30 174947](https://github.com/user-attachments/assets/5af4dba8-162d-4c9d-8e71-a08c3f34cee5)






