[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / GiftItem

# Class: GiftItem

Define a gift item.

## Extended by

- [`PercentGiftItem`](PercentGiftItem.md)

## Constructors

### new GiftItem()

> **new GiftItem**(`typeId`, `reward`, `sound`?): [`GiftItem`](GiftItem.md)

#### Parameters

• **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

• **reward**: [`RewardType`](../interfaces/RewardType.md)

Rewards of the gift.

• **sound?**: `string`

Plays a sound when player receive the reward.

#### Returns

[`GiftItem`](GiftItem.md)

#### Defined in

item/gift.ts:46

## Properties

### reward

> **reward**: [`RewardType`](../interfaces/RewardType.md)

Rewards of the gift.

#### Defined in

item/gift.ts:48

***

### sound?

> `optional` **sound**: `string`

Plays a sound when player receive the reward.

#### Defined in

item/gift.ts:49

***

### typeId

> `readonly` **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

#### Defined in

item/gift.ts:47

## Methods

### giveReward()

> **giveReward**(`player`): `void`

Give reward to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

item/gift.ts:62

***

### ~~register()~~

> `protected` **register**(): `void`

Registry the gift.

#### Returns

`void`

#### Deprecated

Use `Register.giftRegistry()` to registry the gift.

#### Defined in

item/gift.ts:55
