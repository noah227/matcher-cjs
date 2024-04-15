# matcher-cjs

> A CommonJS version of [matcher](https://www.npmjs.com/package/matcher)
>
> For some reason, I have to use `matcher` in a CommonJs style. If you meet the same case, this pkg will help.
> 
> **Remind**: Generally, it's possible to use `matcher` with `import` in your nodejs project, see [Pure ESM package](https://gist.github.com/sindresorhus/a39789f98801d908bbc7ff3ecc99d99c), in which case, you don't need this cjs package.

## Usage

``` js
const {isMatch} = require("matcher-cjs")

console.log(isMatch("unicorn", "uni*"))
```
