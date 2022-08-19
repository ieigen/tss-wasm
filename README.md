# TSS WASM
portable lightweight client application for threshold ECDSA (based on [GG18](https://eprint.iacr.org/2019/114.pdf)), built on&for [multi-party-ecdsa](https://github.com/ZenGo-X/multi-party-ecdsa) : 
1) Wasm
2) HW friendly

# Dev

```
yarn build
yarn test
```

# Npm publish

* node: yarn build_node
* web: yarn build

## Latest release

```
@ieigen/tss-wasm: 0.0.4
@ieigen/tss-wasm-node: 0.0.1, node 18.0+ is required
```

# SM Server
The SM Server currently is built on modified [ZengoX Multiparty ECDSA](https://github.com/eigmax/multi-party-ecdsa)

# licence
GPL & Apache-2.0
