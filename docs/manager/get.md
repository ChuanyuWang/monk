# `manager.get`

Gets a collection.

#### Arguments

1. `name` *(string)*: name of the mongo collection

2. [`options`] *(object)*: collection level options

#### Returns

A [Collection](../collection/README.md) instance.

#### Example

```js
const users = db.get('users', options)
```
