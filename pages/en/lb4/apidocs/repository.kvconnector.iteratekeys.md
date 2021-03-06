---
lang: en
title: 'API docs: repository.kvconnector.iteratekeys'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.kvconnector.iteratekeys.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [KVConnector](./repository.kvconnector.md) &gt; [iterateKeys](./repository.kvconnector.iteratekeys.md)

## KVConnector.iterateKeys() method

Get an Iterator for matching keys

<b>Signature:</b>

```typescript
iterateKeys?(modelClass: Class<Entity>, filter?: Filter, options?: Options): Promise<Iterator<T>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelClass | <code>Class&lt;Entity&gt;</code> | Model class |
|  filter | <code>Filter</code> | Matching filter |
|  options | <code>Options</code> | Options for the operation |

<b>Returns:</b>

`Promise<Iterator<T>>`

A promise of an iterator of entries


