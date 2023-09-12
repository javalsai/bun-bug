# Expected Behaviour

The desired behaviour is that running `bun run lint` would run eslint properly and show a error related to no-console rule on the `index.ts` file.

# Observed Behaviour
Instead of that, if we install the dependencies with `bun i`, eslint can't find the typescrypt plugin and reccommends to install them.

# npm i
But if we use `npm i` instead, the process goes as expected, that means that bun does something wrong on the installation of dependencies or they are installed in a way that eslint can't find.
