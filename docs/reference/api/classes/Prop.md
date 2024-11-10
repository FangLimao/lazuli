[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / Prop

# Class: Prop

A simple prop *(an item that can be used)* , can only be used once.

## Extended by

- [`DurabilityLimitedProp`](DurabilityLimitedProp.md)
- [`NumberLimitedProp`](NumberLimitedProp.md)

## Constructors

### new Prop()

> **new Prop**(`typeId`, `useEvent`?): [`Prop`](Prop.md)

#### Parameters

• **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

• **useEvent?**

The event when an item is successfully used by a player.

#### Returns

[`Prop`](Prop.md)

#### Defined in

item/prop.ts:12

## Properties

### typeId

> `readonly` **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

#### Defined in

item/prop.ts:13

***

### useEvent()?

> `optional` **useEvent**: (`arg`) => `void`

The event when an item is successfully used by a player.

#### Parameters

• **arg**: `ItemUseAfterEvent`

#### Returns

`void`

#### Defined in

item/prop.ts:14

## Methods

### ~~register()~~

> `protected` **register**(): `void`

Registry the prop.

#### Returns

`void`

#### Deprecated

Use `Register.propRegistry()` to registry the prop

#### Defined in

item/prop.ts:20
