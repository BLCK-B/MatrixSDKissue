# MatrixSDKissue

Minimal example of matrix-js-sdk issue.

(node:22444) Warning: To load an ES module, set "type": "module" in the package.json or use the .mjs extension.
(Use `node --trace-warnings ...` to show where the warning was created)
...\node_modules\matrix-js-sdk\lib\index.js:17
import * as matrixcs from "./matrix";
^^^^^^
SyntaxError: Cannot use import statement outside a module

Steps:
- npm install
- npm start
