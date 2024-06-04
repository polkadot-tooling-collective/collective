# Mission List

This list states the projects that PoToC maintains, as required by the [constitution](https://github.com/polkadot-tooling-collective/constitution):

(this is a draft for anyone to comment on and challenge the decisions)

## dApp Developer Tooling

Quote from the constitution:
>This category contains all tools and libraries that help to build on Polkadot and are predominantly developed for this cause. Ideally, it should provide all pieces of software that are needed for a developer to build a dApp on Polkadot.
>
>It specifically aims at developers - not end-users. Things like wallets, explorers, dashboards etc. are out of scope for this very cause.

### Fundamentals

>Software that lays the basis for a dApp project. They connect to the Polkadot network and offer rich possibilities to interact with it.  
Some examples would be: sending transactions, subscribing to block headers or decoding and storage. 

- [Polkadot-JS API](https://github.com/polkadot-js/api)
- [PAPI](https://www.npmjs.com/package/@polkadot-api/substrate-client)
- [SubXt](https://github.com/paritytech/subxt)
- [Substrate Connect](https://github.com/paritytech/substrate-connect)
- [asset-transfer-api](https://github.com/paritytech/asset-transfer-api)
- [asset-transfer-api-registry](https://github.com/paritytech/asset-transfer-api-registry)
- [txwrapper-core](https://github.com/paritytech/txwrapper-core)
- [Zondax/ledger-substrate-js](https://github.com/zondax/ledger-substrate-js)
- [Scale TS](https://npmjs.com/package/scale-ts)
- [scale-*](https://github.com/paritytech/scale-decode), [more](https://github.com/polkadot-tooling-collective/collective/blob/dd96bc056dfa47f0bc6a885c7afd25ed78345a11/join_request/jameswilson.yml#L26)

### Extensions

>Software in this tier depends on Fundamentals and extends their functionality. They may simplify and/or abstract certain functionality or tailor it to suite specific corner needs.

- [Zombienet](https://github.com/paritytech/zombienet) + [v2](https://github.com/paritytech/zombienet-sdk)
- [Chopsticks](https://github.com/AcalaNetwork/chopsticks)
- [Polkadot UI](https://github.com/polkadot-ui/library)
- [Sidecar](https://github.com/paritytech/substrate-api-sidecar)
- [Polkadot-JS Tools](https://github.com/polkadot-js/tools)
- [Subway](https://github.com/AcalaNetwork/subway)
- [virto SDK/libwallet](https://github.com/virto-network/virto-sdk/tree/main/libwallet)
- [virto SDK/scales](https://github.com/virto-network/virto-sdk/tree/main/scales)
- [virto SDK/sube](https://github.com/virto-network/virto-sdk/tree/main/sube)
- [XCM Template](https://github.com/ltfschoen/XCMTemplate)

## General Developer Tooling

>Projects that improve velocity and simplicity to develop on Polkadot. This category is not restricted to dApps, but can also include CLIs and similar.

- [srtool](https://github.com/paritytech/srtool) (maintainer did not apply yet)
- [subwasm](https://github.com/chevdor/subwasm) (ditto)
- [Zepter](https://github.com/ggwpez/zepter)
- [OpenGov CLI](https://github.com/joepetrowski/opengov-cli)
- [Substrate Weight Compare](https://github.com/ggwpez/substrate-weight-compare)

<!--

(this section is not rendered)

## Excluded

- [polkadot-JS extension](https://github.com/polkadot-js/extension): not a developer tool but end-user app.
- [cypress polkadot wallet](https://github.com/ChainSafe/cypress-polkadot-wallet): ditto
- [Zondax Ledger](https://github.com/zondax/ledger-polkadot): ditto
- [Rust Test](https://github.com/ltfschoen/RustTest): research project
- [Polkadot JS test](https://github.com/ltfschoen/PolkadotJSTest)
- [NFT coretime](https://github.com/ltfschoen/nft-coretime): no project description or explanation
- [Flappy tips](https://github.com/ltfschoen/flappytips): game

-->
