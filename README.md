# Laboratoria/schemas


[![Build Status](https://travis-ci.com/Laboratoria/schemas.svg?branch=master)](https://travis-ci.com/Laboratoria/schemas)

## Installation

## Usage

### Browser

```js
import mongoose from 'mongoose/browser';
import schemas from 'schemas';

const { validate } = schemas(mongoose);

validate('Project', {
  slug: 'cipher',
  repo: 'Laboratoria/curricula-js',
  path: 'projects/01-cipher',
  // ...
}, (err) => {
  if (err) {
    // validation failed ...
  }

  // ...
});
```

### Node.js

Ver Laboratoria/models!!!

```js
const mongoose = require('mongoose');
const { validate } = require('schemas')(mongoose);

// ...
```
