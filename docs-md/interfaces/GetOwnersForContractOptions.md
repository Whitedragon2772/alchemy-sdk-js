[alchemy-sdk](../README.md) / [Exports](../modules.md) / GetOwnersForContractOptions

# Interface: GetOwnersForContractOptions

Optional parameters object for the [getNftsForContract](../classes/NftNamespace.md#getnftsforcontract) method.

This interface configures options when fetching the owner addresses of the
provided contract.

## Table of contents

### Properties

- [block](GetOwnersForContractOptions.md#block)
- [pageKey](GetOwnersForContractOptions.md#pagekey)
- [withTokenBalances](GetOwnersForContractOptions.md#withtokenbalances)

## Properties

### block

• `Optional` **block**: `string`

The block number in hex or decimal to fetch owners for.

#### Defined in

[src/types/types.ts:917](https://github.com/alchemyplatform/alchemy-sdk-js/blob/5944626/src/types/types.ts#L917)

___

### pageKey

• `Optional` **pageKey**: `string`

Optional page key to paginate the next page for large requests.

#### Defined in

[src/types/types.ts:920](https://github.com/alchemyplatform/alchemy-sdk-js/blob/5944626/src/types/types.ts#L920)

___

### withTokenBalances

• `Optional` **withTokenBalances**: `boolean`

Whether to include the token balances per token id for each owner. Defaults
to false when omitted.

#### Defined in

[src/types/types.ts:914](https://github.com/alchemyplatform/alchemy-sdk-js/blob/5944626/src/types/types.ts#L914)
