# hashtagfy2

Convert any text to #hashtag.
This fork of <a href="https://www.npmjs.com/package/hashtagfy">hashtagfy</a> replace string template with string concatenation.

## Installation
```
npm install --save hashtagfy2
```

## How to use

```javascript
const hashtagfy = require('hashtagfy2')

const hashtag1 = hashtagfy('Any text');
// hashtag1 == '#AnyText'

const hashtag2 = hashtagfy('Similar-text_more');
// hashtag2 == '#SimilarTextMore'

const hashtag3 = hashtagfy('And the last', { capitalize: false });
// hashtag3 == '#andthelast'
```

NOTE: The `capitalize` option is optional. Is `true` by default.