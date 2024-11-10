[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / DurabilityLimitedProp

# Class: DurabilityLimitedProp

A prop *(an item that can be used)* , Its durability is consumed after use.

## Extends

- [`Prop`](Prop.md)

## Constructors

### new DurabilityLimitedProp()

> **new DurabilityLimitedProp**(`typeId`, `durabilityValue`, `useEvent`?): [`DurabilityLimitedProp`](DurabilityLimitedProp.md)

#### Parameters

• **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

• **durabilityValue**: `number`

The durability to be consumed.

• **useEvent?**

The event when an item is successfully used by a player.

#### Returns

[`DurabilityLimitedProp`](DurabilityLimitedProp.md)

#### Overrides

[`Prop`](Prop.md).[`constructor`](Prop.md#constructors)

#### Defined in

item/prop.ts:35

## Properties

### durabilityValue

> **durabilityValue**: `number`

The durability to be consumed.

#### Defined in

item/prop.ts:37

***

### typeId

> `readonly` **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

#### Inherited from

[`Prop`](Prop.md).[`typeId`](Prop.md#typeid)

#### Defined in

item/prop.ts:36

***

### useEvent()?

> `optional` **useEvent**: (`arg`) => `void`

The event when an item is successfully used by a player.

#### Parameters

• **arg**: `ItemUseAfterEvent`

#### Returns

`void`

#### Inherited from

[`Prop`](Prop.md).[`useEvent`](Prop.md#useevent)

#### Defined in

item/prop.ts:38

## Methods

### ~~register()~~

> `protected` **register**(): `void`

Registry the prop.

#### Returns

`void`

#### Deprecated

Use `Register.propRegistry()` to registry the prop

#### Inherited from

[`Prop`](Prop.md).[`register`](Prop.md#register)

#### Defined in

item/prop.ts:20
