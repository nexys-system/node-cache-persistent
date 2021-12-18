# Node Cache

[![npm version](https://img.shields.io/npm/v/@nexys/node-cache.svg)](https://www.npmjs.com/package/@nexys/node-cache)
[![Build and Test Package](https://github.com/nexys-system/node-cache-persistent/actions/workflows/yarn.yml/badge.svg)](https://github.com/nexys-system/node-cache-persistent/actions/workflows/yarn.yml)
[![Publish](https://github.com/nexys-system/node-cache-persistent/actions/workflows/publish.yml/badge.svg)](https://github.com/nexys-system/node-cache-persistent/actions/workflows/publish.yml)
![Code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)
[![Bundlephobia](https://badgen.net/bundlephobia/min/@nexys/node-cache)](https://bundlephobia.com/result?p=@nexys/node-cache)

Expands [node-cache](https://www.npmjs.com/package/node-cache) and adds `persistent` option.

## get started

```
const Cache from '@nexys/node-cache';

const cache = new Cache({ persistent: true });

export default cache;
```
