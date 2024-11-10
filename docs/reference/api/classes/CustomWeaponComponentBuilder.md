[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / CustomWeaponComponentBuilder

# Class: CustomWeaponComponentBuilder

Build a custom weapon component, **it doesn`t support weapon skill.**

## Example

```ts
new CustomWeaponComponentBuilder("ldk:example_component").build();
```

## Constructors

### new CustomWeaponComponentBuilder()

> **new CustomWeaponComponentBuilder**(`typeId`, `options`?): [`CustomWeaponComponentBuilder`](CustomWeaponComponentBuilder.md)

#### Parameters

• **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

• **options?**: [`WeaponOptions`](../interfaces/WeaponOptions.md)

Additional options of the weapon, **it doesn`t support weapon skill**.

#### Returns

[`CustomWeaponComponentBuilder`](CustomWeaponComponentBuilder.md)

#### Defined in

component.ts:242

## Properties

### options?

> `optional` **options**: [`WeaponOptions`](../interfaces/WeaponOptions.md)

Additional options of the weapon, **it doesn`t support weapon skill**.

#### Defined in

component.ts:244

***

### typeId

> `readonly` **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

#### Defined in

component.ts:243

## Methods

### build()

> **build**(): `void`

#### Returns

`void`

#### Defined in

component.ts:246
