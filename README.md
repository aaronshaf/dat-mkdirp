```javascript
const mkdirp = require("dat-mkdirp");

async function main(archive) {
  await mkdirp("/foo/bar", archive);
}

main(archive);
```
