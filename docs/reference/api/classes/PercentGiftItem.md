[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / PercentGiftItem

# Class: PercentGiftItem

A Percent-Driven random reward gift.

## Extends

- [`GiftItem`](GiftItem.md)

## Constructors

### new PercentGiftItem()

> **new PercentGiftItem**(`typeId`, `chance`, `reward`, `sound`?): [`PercentGiftItem`](PercentGiftItem.md)

#### Parameters

• **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

• **chance**: `number`

The probability of give reward when use the gift, should be a percentage (0~1).

• **reward**: [`RewardType`](../interfaces/RewardType.md)

Rewards of the gift.

• **sound?**: `string`

Plays a sound when player receive the reward.

#### Returns

[`PercentGiftItem`](PercentGiftItem.md)

#### Overrides

[`GiftItem`](GiftItem.md).[`constructor`](GiftItem.md#constructors)

#### Defined in

item/gift.ts:78

## Properties

### chance

> **chance**: `number`

The probability of give reward when use the gift, should be a percentage (0~1).

#### Defined in

item/gift.ts:80

***

### reward

> **reward**: [`RewardType`](../interfaces/RewardType.md)

Rewards of the gift.

#### Inherited from

[`GiftItem`](GiftItem.md).[`reward`](GiftItem.md#reward)

#### Defined in

item/gift.ts:81

***

### sound?

> `optional` **sound**: `string`

Plays a sound when player receive the reward.

#### Inherited from

[`GiftItem`](GiftItem.md).[`sound`](GiftItem.md#sound)

#### Defined in

item/gift.ts:82

***

### typeId

> `readonly` **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

#### Inherited from

[`GiftItem`](GiftItem.md).[`typeId`](GiftItem.md#typeid)

#### Defined in

item/gift.ts:79

## Methods

### giveReward()

> **giveReward**(`player`): `void`

Give reward to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Overrides

[`GiftItem`](GiftItem.md).[`giveReward`](GiftItem.md#givereward)

#### Defined in

item/gift.ts:90

***

### ~~register()~~

> `protected` **register**(): `void`

Registry the gift.

#### Returns

`void`

#### Deprecated

Use `Register.giftRegistry()` to registry the gift.

#### Inherited from

[`GiftItem`](GiftItem.md).[`register`](GiftItem.md#register)

#### Defined in

item/gift.ts:55
