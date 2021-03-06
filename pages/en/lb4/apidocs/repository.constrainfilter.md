---
lang: en
title: 'API docs: repository.constrainfilter'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.constrainfilter.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [constrainFilter](./repository.constrainfilter.md)

## constrainFilter() function

A utility function which takes a filter and enforces constraint(s) on it

<b>Signature:</b>

```typescript
export declare function constrainFilter<T extends object>(originalFilter: Filter<T> | undefined, constraint: AnyObject): Filter<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  originalFilter | <code>Filter&lt;T&gt; &#124; undefined</code> | the filter to apply the constrain(s) to |
|  constraint | <code>AnyObject</code> | the constraint which is to be applied on the filter |

<b>Returns:</b>

`Filter<T>`

Filter the modified filter with the constraint, otherwise the original filter


