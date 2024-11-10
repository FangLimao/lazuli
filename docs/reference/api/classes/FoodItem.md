[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / FoodItem

# Class: FoodItem

Define a food item.

## Constructors

### new FoodItem()

> **new FoodItem**(`typeId`, `statusEffects`?, `eatEvent`?): [`FoodItem`](FoodItem.md)

#### Parameters

• **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

• **statusEffects?**: `EffectData`[]

Adds a status effect when entity eat the food.

• **eatEvent?**

This event fires when eat the food.

#### Returns

[`FoodItem`](FoodItem.md)

#### Defined in

item/food.ts:14

## Properties

### eatEvent()?

> `optional` **eatEvent**: (`arg`) => `void`

This event fires when eat the food.

#### Parameters

• **arg**: `ItemCompleteUseAfterEvent`

#### Returns

`void`

#### Defined in

item/food.ts:17

***

### statusEffects?

> `optional` **statusEffects**: `EffectData`[]

Adds a status effect when entity eat the food.

#### Defined in

item/food.ts:16

***

### typeId

> `readonly` **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

#### Defined in

item/food.ts:15

## Methods

### ~~register()~~

> `protected` **register**(): `void`

Registry the food.

#### Returns

`void`

#### Deprecated

Use `Register.foodRegistry()` to registry the food.

#### Defined in

item/food.ts:23
