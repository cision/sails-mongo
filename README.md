[![](https://camo.githubusercontent.com/9e49073459ed4e0e2687b80eaf515d87b0da4a6b/687474703a2f2f62616c64657264617368792e6769746875622e696f2f7361696c732f696d616765732f6c6f676f2e706e67)](http://sailsjs.com)

# sails-mongo
[![npm version](https://badge.fury.io/js/sails-mongo.svg)](http://badge.fury.io/js/sails-mongo)

Extensions to Sails.js/Waterline adapter for MongoDB.

See https://github.com/balderdashy/sails-mongo for configuration and other documentation.

Extended Features Include

Forked Features List
Added Support for regex filters.
> API Syntax = where={"field": {"regex": "expression"}}

Noted
> **Heads up**
>
> `sails-mongo` maps the logical `id` attribute to the required `_id` physical-layer mongo id.
> In the current version of `sails-mongo`, you **should not** sort by `id`.


## Installation

Install from NPM.

```bash
$ npm install cision@sails-mongo --save
```
