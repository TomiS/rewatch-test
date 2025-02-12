# Rewatch Test

Testing monorepo configuration with Rewatch

Uses yarn 1.22 for dependencies (included in devcontainer)

- Checkout repository
- Open in VSCode. Say yes to "rebuild in container" prompt.
- Run `yarn install` in vscode terminal
- Run `yarn build` in vscode terminal

Issues

- After running `rewatch build .` (or `yarn build`), there should be commonjs javascript generated for backend source code. There is none.
- No `.gen.tsx` files are generated into frontend nor shared folder even if the configuration for that exists.