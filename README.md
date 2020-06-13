# lz4-ts

This is a TypeScript port of https://github.com/pierrec/lz4.

```TypeScript
function calcUncompressedLen(src: Uint8Array): number;
function uncompressBlock(src: Uint8Array, dest: Uint8Array): number;
function compressBlockBound(n: number): number;
function compressBlock(src: Uint8Array, dest: Uint8Array, soffset: number): number;
function compressBlockHC(src: Uint8Array, dest: Uint8Array, soffset: number): number;
```

## LICENSE

See [LICENSE](./LICENSE)
