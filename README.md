# pinterpolate

[![npm](https://img.shields.io/npm/v/pinterpolate.svg)](https://www.npmjs.com/package/pinterpolate)
[![Build Status](https://travis-ci.org/pratishshr/pinterpolate.svg?branch=master)](https://travis-ci.org/pratishshr/pinterpolate)
[![npm](https://img.shields.io/npm/dt/pinterpolate.svg)](https://www.npmjs.com/package/pinterpolate)

> Simple string formatting.

## Installation

```bash
npm install --save pinterpolate
```

```bash
yarn add pinterpolate
```

Build supplied string by interpolating properties after delimiter ':' with the given parameters.
Useful for formatting strings.

## Usage

```js
import pinterpolate from 'pinterpolate';

pinterpolate('/users/:id', { id: 1 });
// => '/users/1'

pinterpolate(':name is here.', { name: 'Barbara' });
// => 'Barbaba is here.'
```
