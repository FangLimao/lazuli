[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / NumberLimitedProp

# Class: NumberLimitedProp

A prop *(an item that can be used)* , it has a limited number of uses.

## Extends

- [`Prop`](Prop.md)

## Constructors

### new NumberLimitedProp()

> **new NumberLimitedProp**(`typeId`, `options`, `useEvent`?): [`NumberLimitedProp`](NumberLimitedProp.md)

#### Parameters

• **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

• **options**: [`NumberLimitedPropOptions`](../interfaces/NumberLimitedPropOptions.md)

Options of the prop.

• **useEvent?**

The event when an item is successfully used by a player.

#### Returns

[`NumberLimitedProp`](NumberLimitedProp.md)

#### Overrides

[`Prop`](Prop.md).[`constructor`](Prop.md#constructors)

#### Defined in

item/prop.ts:54

## Properties

### options

> **options**: [`NumberLimitedPropOptions`](../interfaces/NumberLimitedPropOptions.md)

Options of the prop.

#### Defined in

item/prop.ts:56

***

### typeId

> `readonly` **typeId**: `string`

Identifier of the type of items for the stack. If a namespace is not specified, 'minecraft:' is assumed.

#### Inherited from

[`Prop`](Prop.md).[`typeId`](Prop.md#typeid)

#### Defined in

item/prop.ts:55

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

item/prop.ts:57

## Methods

### ~~register()~~

> `protected` **register**(): `void`

Registry the prop.

#### Returns

`void`

#### Deprecated

Use `Register.propRegistry()` to registry the prop.

#### Overrides

[`Prop`](Prop.md).[`register`](Prop.md#register)

#### Defined in

item/prop.ts:65
