# Rewatch Test

Testing monorepo configuration with Rewatch

Uses yarn 1.22 for dependencies

- Checkout repository
- Run `yarn install`
- Run `yarn build`

Issues

- After running `rewatch build .` (or `yarn build`), there should be commonjs javascript generated for backend source code. There is none.
- No `.gen.tsx` files are generated into frontend nor shared folder even if the configuration for that exists.