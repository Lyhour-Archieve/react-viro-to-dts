# react-viro-t-dts

Generate typescript defintions for react-viro. Exports rudimentary type definitions for react-viro base on the propTypes for all components.

## Generating .d.ts files

```
npm install
npm start
```
_Note: Definition file is exported to @types/react-viro/index.d.ts_

## Using it in your project

Copy the resulting `./@types` folder to your own project. Make sure you have the following lines in the compilerOptions directive of your `tsconfig.json`:

```
    "typeRoots" : ["node_modules/@types", "./@types"], // If you use custom typeRoots add them to the array
```
