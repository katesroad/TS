# TS

## module

- [export all as x](https://www.typescriptlang.org/docs/handbook/modules.html#export-all-as-x)

```typescript
export * as utilities from "./utilities";
```

## Declare types

- declare a function that the return type is void

```typescript
type Func = (state:boolean) => void

interface ISwitcher {
	onChange: Func
	value: boolean
}
```

- [To describe the shape of libraries not written in TypeScript,](https://www.typescriptlang.org/docs/handbook/modules.html#working-with-other-javascript-libraries)