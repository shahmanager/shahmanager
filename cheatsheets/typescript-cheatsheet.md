# TypeScript Type Helpers Cheatsheet

Utility types in practice:
- `Record<K, T>` / `Partial<T>` / `Required<T>`
- `Pick<T, K>` / `Omit<T, K>`
- `ReturnType<typeof func>` / `Parameters<T>`


## Practical Idioms and Recipes

Pattern matching with conditional types:
- `type Flatten<T> = T extends (infer U)[] ? U : T;`
- `type NonNullable<T> = T & {};`
