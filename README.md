# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules
Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) 
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) 

## Expanding the ESLint configuratio
If you are developing a production applica
- Configure the top-level `parserOpti
export default tseslint.co
  languageOpt
    // other options
    parserOptions
      project: ['./tsc
      tsconfigRoot

  }
```

- Replace `tseslint.configs.recommended` to `tseslint.configs.recommendedTypeChecked`
- Optionally add `...tseslint.configs.stylisticTypeChec
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-reac
```j
// eslint.config.j
import react from 'eslint-plugin-reac

export default tseslint.config({
  // Set the react version
  settings: { react: { version: '18.3' } }
  plugins: {
    // Add the react plugin
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
