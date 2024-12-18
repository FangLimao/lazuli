[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / WeightGiftItem

# Class: WeightGiftItem

A Weight-Driven random reward gift.

## Constructors

### new WeightGiftItem()

> **new WeightGiftItem**(`typeId`, `data`, `sound`?): [`WeightGiftItem`](WeightGiftItem.md)

#### Parameters

• **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

• **data**: [`RewardWeightData`](../interfaces/RewardWeightData.md)[]

Data of the gift, including its reward and weight.

• **sound?**: `string`

Plays a sound when player receive the reward.

#### Returns

[`WeightGiftItem`](WeightGiftItem.md)

#### Defined in

item/gift.ts:116

## Properties

### data

> **data**: [`RewardWeightData`](../interfaces/RewardWeightData.md)[]

Data of the gift, including its reward and weight.

#### Defined in

item/gift.ts:118

***

### sound?

> `optional` **sound**: `string`

Plays a sound when player receive the reward.

#### Defined in

item/gift.ts:119

***

### typeId

> `readonly` **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

#### Defined in

item/gift.ts:117

## Methods

### giveReward()

> **giveReward**(`player`): `void`

Give reward to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

item/gift.ts:132

***

### ~~register()~~

> `protected` **register**(): `void`

Registry the gift.

#### Returns

`void`

#### Deprecated

Use `Register.giftRegistry()` to registry the gift.

#### Defined in

item/gift.ts:125
