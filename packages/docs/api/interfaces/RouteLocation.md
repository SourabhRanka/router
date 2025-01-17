---
editLink: false
---

[API Documentation](../index.md) / RouteLocation

# Interface: RouteLocation

[RouteLocationRaw](../index.md#routelocationraw) resolved using the matcher

## Hierarchy %{#Hierarchy}%

- `_RouteLocationBase`

  ↳ **`RouteLocation`**

## Properties %{#Properties}%

### fullPath %{#Properties-fullPath}%

• **fullPath**: `string`

The whole location including the `search` and `hash`. This string is
percentage encoded.

#### Inherited from %{#Properties-fullPath-Inherited-from}%

\_RouteLocationBase.fullPath

___

### hash %{#Properties-hash}%

• **hash**: `string`

Hash of the current location. If present, starts with a `#`.

#### Inherited from %{#Properties-hash-Inherited-from}%

\_RouteLocationBase.hash

___

### matched %{#Properties-matched}%

• **matched**: [`RouteRecordNormalized`](RouteRecordNormalized.md)[]

Array of [RouteRecord](../index.md#routerecord) containing components as they were
passed when adding records. It can also contain redirect records. This
can't be used directly

___

### meta %{#Properties-meta}%

• **meta**: [`RouteMeta`](RouteMeta.md)

Merged `meta` properties from all the matched route records.

#### Inherited from %{#Properties-meta-Inherited-from}%

\_RouteLocationBase.meta

___

### name %{#Properties-name}%

• **name**: `undefined` \| ``null`` \| [`RouteRecordName`](../index.md#Type-Aliases-RouteRecordName)

Name of the matched record

#### Inherited from %{#Properties-name-Inherited-from}%

\_RouteLocationBase.name

___

### params %{#Properties-params}%

• **params**: [`RouteParams`](../index.md#routeparams)

Object of decoded params extracted from the `path`.

#### Inherited from %{#Properties-params-Inherited-from}%

\_RouteLocationBase.params

___

### path %{#Properties-path}%

• **path**: `string`

Percentage encoded pathname section of the URL.

#### Inherited from %{#Properties-path-Inherited-from}%

\_RouteLocationBase.path

___

### query %{#Properties-query}%

• **query**: [`LocationQuery`](../index.md#locationquery)

Object representation of the `search` property of the current location.

#### Inherited from %{#Properties-query-Inherited-from}%

\_RouteLocationBase.query

___

### redirectedFrom %{#Properties-redirectedFrom}%

• **redirectedFrom**: `undefined` \| [`RouteLocation`](RouteLocation.md)

Contains the location we were initially trying to access before ending up
on the current location.

#### Inherited from %{#Properties-redirectedFrom-Inherited-from}%

\_RouteLocationBase.redirectedFrom
