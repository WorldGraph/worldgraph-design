# IPFS / ipld interaction

Standards behind IPLD encoding and formats are evolving rapidly.  See [here](https://github.com/ipld/js-ipld/issues/295#issuecomment-785868280) for a discussion.

## Building blocks

These are the libraries we will build on top of for interaction with IPFS in the IPLD format.

1. [js-ipfs](https://github.com/ipfs/js-ipfs/blob/e25091ca90e99e22a56bcb40d8e415d22f5a13c4/docs/core-api/BLOCK.md) - core IPFS block API https://github.com/multiformats/js-multiformats
2. [js-ipld-schema-validator](https://github.com/rvagg/js-ipld-schema-validator) - validate IPLD schema prior to writing to IPFS
3. [js-multiformats](https://github.com/multiformats/js-multiformats) - Tools for "core" IPFS, e.g. codecs

## Under investigation

1. [ceramic](https://blog.ceramic.network/how-to-store-signed-and-encrypted-data-on-ipfs/) - for signing (and optionally encrypting) data on IPFS.
2. [IPLD Schema](https://github.com/ipld/js-ipld-schema)
3. [IPFS HTTP Client](https://github.com/ipfs/js-ipfs/tree/master/packages/ipfs-http-client)