# markdown-it-hierarchy

> Adds numbering hierarchy to [markdown-it] headers.

[markdown-it]: https://github.com/markdown-it/markdown-it

```js
const md = require('markdown-it')()
  .use(require('markdown-it-hierarchy'));
```

Will produce hierarchy of headers like following:

# 1. First header of top level
## 1.1. First subheader of first header
## 1.2. Second subheader of first header
## 1.3. Third subheader of first header
# 2. Second header of top level
# 3. Third header of top level
## 3.1. First subheader of third header
## 3.1.1. First subheader of first subheader of third header
## 3.1.2. Second subheader of first subheader of third header
## 3.1.3. Third subheader of first subheader of third header