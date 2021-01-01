# [shitpostify](https://www.npmjs.com/package/shitpostify)

Simple NPM module requiring 0 dependencies. Takes a string that you pass it, and returns a promise that resolves with random capitalization and a random emoji in each space. Associated with my [Chrome Extension of the same name](https://chrome.google.com/webstore/detail/shitpostify/dojihbiflikelfjnoaljoeiklhgdnijp?hl=en-US).

Sample usage:

```js
const shitpostify = require('shitpostify');

const sp = await shitpostify("Hey dude, if you don't stop turning my comments into emojis, I'm gonna smash your laptop");

console.log(sp);
// Hey📱dUDE,🏑iF🦅yoU◼️DoN'T🏌️‍♂️STOp🌅TurniNg🎆My👲COMMEnTS🍲intO🏄‍♂️emoJIs,🎱i'm⚓gONnA🐄SmASH🥣yOUr🆕LaPtOp
```