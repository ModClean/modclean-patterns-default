# modclean-patterns-default
[![npm version](https://img.shields.io/npm/v/modclean-patterns-default.svg)](https://www.npmjs.com/package/modclean-patterns-default) [![NPM Downloads](https://img.shields.io/npm/dm/modclean-patterns-default.svg)](https://www.npmjs.com/package/modclean-patterns-default) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/ModClean/modclean-patterns-default/master/LICENSE) [![GitHub issues](https://img.shields.io/github/issues/ModClean/modclean-patterns-default.svg)](https://github.com/ModClean/modclean-patterns-default/issues)

Default patterns configuration for ModClean 2.x. This module is automatically installed when installing ModClean.

## Install
**Note:** This module is included by default with ModClean 2.x.

### Install Globally (for ModClean CLI)
```
npm install -g modclean-patterns-default
```

### Install Locally (for ModClean API)
```
npm install modclean-patterns-default --save-dev
```

## Available Configurations

### default:safe
Contains patterns that are considered safe and should not affect your application. It also removes the most files/folders of all the configurations.

### default:caution
Contains patterns that could potentially cause issues with modules, but includes patterns that will help reduce your modules folder size.

### default:danger
Contains patterns that are known to cause issues with certain modules, but can help reduce files and your modules folder size even further.

---

## Contributing
If you find issues with the patterns or have patterns to add, please either submit a pull request or open an issue.
