# azurlane-protocol-parser

Parses `.proto` profobuf network protocol files for the mobile game Azur Lane from LUA source. If you need help about where to find the source for protocol, you probably don't need this.

## Usage

```js
const fs = require("fs");
const { parse } = require("azurlane-protocol-parser");

const parsedFile = parse(protocolFileSource);
fs.writeFileSync(filePath, parsedFile);
```
