---
id: fast-foundation.container.registerresolver
title: Container.registerResolver() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [Container](./fast-foundation.container.md) &gt; [registerResolver](./fast-foundation.container.registerresolver.md)

## Container.registerResolver() method

Registers a resolver with the container for the specified key.

<b>Signature:</b>

```typescript
registerResolver<K extends Key, T = K>(key: K, resolver: Resolver<T>): Resolver<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  key | K | The key to register the resolver under. |
|  resolver | [Resolver](./fast-foundation.resolver.md)<!-- -->&lt;T&gt; | The resolver to register. |

<b>Returns:</b>

[Resolver](./fast-foundation.resolver.md)<!-- -->&lt;T&gt;