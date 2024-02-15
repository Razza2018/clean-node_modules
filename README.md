# Clean node_modules

This script will delete all *node_modules* directories that are inside the children of the parent directory from where the script is run.

Directory structure example:

- project 1
  - *node_modules*
  - index.js
- project 2
  - *node_modules*
  - index.js
- project 3
  - *node_modules*
  - index.js
- clean-node-modules
  - **clean-node_modules.js**

Running `node clean-node_modules.js` will delete all of the *node_modules* folders.
