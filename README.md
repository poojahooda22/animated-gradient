# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules
Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/)

## Expanding the ESLint configuratio
If you are developing a production appli
export default tseslint.c
  languageOpt
    // other optio
    parserOptio
      project: ['./t
      tscon
  }
``
- Optionally add `...tseslint.confi
- Install [eslint-plugin-react]
// eslint.confi
import react from 'eslint-plugin
export default tseslint.conf
  // Set the react v
  settings: { react: { versi
  plugins: 
    // Add the react pl
    react
  },
  rules: 
    // other rules...
    // Enable its recommended rules
    ...react.configs.recommended.rules,
    ...react.configs['jsx-runtime'].rul
  },
})
```
