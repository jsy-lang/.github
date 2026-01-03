# JSY indented JavaScript
![JSY Logo](./jsy_logo.svg)

JSY is a syntax dialect for ECMAScript using offside indentation
similar to [Python][] or [CoffeeScript][]
from ES5 to ES2025.

- [JSY website](https://jsy-lang.github.io/)
- [JSY syntax dialect](https://github.com/jsy-lang/jsy-lang-docs)

## Use

With [NodeJS][]:
```sh
# Install
> npm install @jsy-lang/jsy @jsy-lang/nodejs

# Use JSY directly via Node CLI
> node --import @jsy-lang/nodejs some-demo.jsy

# See how JSY transpiles
> npx @jsy-lang/jsy some-demo.jsy
```

Or bundle with [Rollup][] or [Vite][] via [`@jsy-lang/jsy/rollup`](https://github.com/jsy-lang/jsy)


 [Python]: https://www.python.org
 [CoffeeScript]: https://coffeescript.org
 [Rollup]: https://rollupjs.org
 [Vite]: https://vitejs.dev
 [NodeJS]: https://nodejs.org
