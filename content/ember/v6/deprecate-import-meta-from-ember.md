---
title: Ember.meta
until: 7.0.0
since: 6.5.0
---


Previously, `meta` could be accessed via the `Ember` import:
```js
import Ember from 'ember';

Ember.meta
```
`meta` is also private.

If needed, `meta` can be imported:
```js
import { meta } from '@ember/-internals/meta';
```

However, due to `meta` being private, it is not recommended, nor supported.
