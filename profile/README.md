# JSY language dialect of JavaScript

JSY is an indented (offside) JavaScript dialect. 
Think modern JavaScript (ES6 to ES2022) but indented similar to [Python][] or [CoffeeScript][]

Inspired by an indented dialect of LISP called [Wisp][],
JSY primarily operates as a scanner-pass syntax transformation to change
indented (offside) code into the corresponding open/close matching token
JavaScript code. Thus the internal scanning parser only has to be aware of
`/* comments */` and `"string literals"` rules to successfully transform code.
Thus, as a dialect, **JSY automatically keeps pace with modern JavaScript editions!**

Our opinion is that indentation is a strong expression of the author's
intention, and should be observed by the language dialect.
As a dialect, JSY leading operators opt into the offside indentation,
and standard JavaScript continues to work without modification.
As a code author, indentation frees you from painstakingly matching open/close
sections `{} () []` so you can focus on the logic.
As a code reader, your screen is uncluttered by lines of closing punctuation --
allowing you to focus on the logic.


### History

This project originally started as [Babel][] extension plugin. In 2018, we
transitioned the project to a scanner-based text transformation library
independent of the Babel ecosystem, designed to work with [Rollup][] and
similar transpilation tools in the JavaScript ecosystem. We've been iterating
it, growing and testing the operators, eating our own dogfood, building an
extensive test suite, and adapting it to new tools like [Parcel][],
[ESBuild][], and [Vite][].


## Version 1.0

Now we feel we are drinking our own champaign; it is time to share a 1.0 version.

I acknowledge the many who strongly dislike indented languages; JSY was not made for you. 
JSY was made for ourselves first -- the thing we wish existed.
And now JSY is offered for everyone who prefers indention over open/close punctuation.
We hope some of you enjoy using it; we certainly do.



 [Python]: https://www.python.org
 [CoffeeScript]: https://coffeescript.org
 [Wisp]: http://www.draketo.de/english/wisp
 [Babel]: https://babeljs.io
 [Rollup]: https://rollupjs.org
 [Parcel]: https://parceljs.org
 [ESBuild]: https://esbuild.github.io
 [Vite]: https://vitejs.dev
