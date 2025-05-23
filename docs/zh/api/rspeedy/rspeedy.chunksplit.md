<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@lynx-js/rspeedy](./rspeedy.md) &gt; [ChunkSplit](./rspeedy.chunksplit.md)

## ChunkSplit interface

[Performance.chunkSplit](./rspeedy.performance.chunksplit.md) is used to configure the chunk splitting strategy.

**Signature:**

```typescript
export interface ChunkSplit 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [override?](./rspeedy.chunksplit.override.md) |  | Rspack.Configuration extends { optimization?: { splitChunks?: infer P; } \| undefined; } ? P : never | _(Optional)_ Custom Rspack chunk splitting config can be specified. |
|  [strategy?](./rspeedy.chunksplit.strategy.md) |  | 'all-in-one' \| 'split-by-module' \| 'split-by-experience' \| 'single-vendor' \| undefined | _(Optional)_ The ChunkSplitting strategy. |

