# JSY indented JavaScript

JSY is a syntax dialect for ECMAScript using offside indentation
similar to [Python][] or [CoffeeScript][]
from ES5 to ES2023.

- [JSY website](https://jsy-lang.github.io/)
- [JSY syntax dialect](https://github.com/jsy-lang/jsy-lang-docs)

## Use

With [NodeJS][]:
```sh
# Use JSY directly via loader plugin
> node --loader @jsy-lang/nodejs some-demo.jsy

# See how JSY transpiles
> npx @jsy-lang/jsy some-demo.jsy
```

Or bundle with [Rollup][] or [Vite][] via [`rollup-plugin-jsy`](https://github.com/jsy-lang/rollup-plugin-jsy)


 [Python]: https://www.python.org
 [CoffeeScript]: https://coffeescript.org
 [Rollup]: https://rollupjs.org
 [Vite]: https://vitejs.dev
 [NodeJS]: https://nodejs.org
