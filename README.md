# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules
Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) 

## Expanding the ESLint configuratio
If you are developing a production applic
- Configure the top-level `parserOp
export default tseslint.c
  languageOpt
    // other options
    parserOptions
      project: ['./tsc
      tsconfi
  }
``
- Optionally add `...tseslint.configs
- Install [eslint-plugin-react](htt
// eslint.confi
import react from 'eslint-plugin-re
export default tseslint.confi
  // Set the react vers
  settings: { react: { version: '18.
  plugins: {
    // Add the react plugi
    react,
  },
  rules: {
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rules,
  },
})
```
