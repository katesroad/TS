# TS

## tsconfig.json explained

https://www.typescriptlang.org/docs/handbook/tsconfig-json.html

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

- [Module exports practice](https://www.typescriptlang.org/docs/handbook/modules.html#export-as-close-to-top-level-as-possible)


## React

- [checksheet](https://github.com/typescript-cheatsheets/react)

- input change event
	- code 
	```typescript
	onChange = (e: React.ChangeEvent<HTMLInputElement>)=> {
	   const newValue = e.target.value;
	}
	```
	- reference: [https://stackoverflow.com/questions/40676343/typescript-input-onchange-event-target-value](https://stackoverflow.com/questions/40676343/typescript-input-onchange-event-target-value)
- select change event
	- code
	```typescript
	onChange = (e: React.ChangeEvent<HTMLSelectElement>)=> {
	   const newValue = e.target.value;
	}
	```
## Practices
 - [How to use typescript in big projects](https://www.youtube.com/watch?v=RnTU81aQMRA)
