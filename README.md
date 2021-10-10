# apputils

Basic helper functions for HTTP requests, file system, logging, JSON parsing and other basics of a web app.

## Installation

```
npm install @JLTG2018/apputils
```

## Usage

At the top of your source code file write:

with TypeScript:
```
import * as utils from "@JLTG2018/apputils";
const logger = utils.logger
    , nconf = utils.nconf;
```

with JavaScript:
```
const utils = require("@JLTG2018/apputils");
const logger = utils.logger
    , nconf = utils.nconf;
```