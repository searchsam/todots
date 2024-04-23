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
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

https://www.youtube.com/watch?v=4lAYfsq-2TE
- [x] Creando proyecto con Vite
- [x] Linter para React y TypeScript
- [x] Sobre los estilos de la aplicación
- [x] Cómo indicar el tipo de las funciones
- [x] Renderizando lista de tareas
- [x] Tipos de props con TypeScript en React
- [x] Type vs Interface en TypeScript
- [x] Usando React.FC
- [x] Extrayendo tipos a un fichero
- [x] Creando componente Todo
- [x] Funcionalidad poder borrar Todos
- [x] Buena práctica a la hora de tratar con tipos primitivos
- [ ] Indicar Todo como completado
- [ ] Crear una forma de filtrar todos
- [ ] ¿TypeScript te ralentiza o te hace ir más rápido?
- [ ] Borrar todos los todos completados
- [ ] Crear un nuevo Todo