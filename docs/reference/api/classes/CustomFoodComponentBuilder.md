[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / CustomFoodComponentBuilder

# Class: CustomFoodComponentBuilder

Build a custom food component.

## Example

```ts
new CustomFoodComponentBuilder("ldk:example_component", [{
    effectType: "poison",
    duration: 20
}]).build();
```

## Constructors

### new CustomFoodComponentBuilder()

> **new CustomFoodComponentBuilder**(`typeId`, `statusEffects`?, `eatEvent`?): [`CustomFoodComponentBuilder`](CustomFoodComponentBuilder.md)

#### Parameters

• **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

• **statusEffects?**: `EffectData`[]

Adds a status effect when eat the food.

• **eatEvent?**

This event fires when eat the food.

#### Returns

[`CustomFoodComponentBuilder`](CustomFoodComponentBuilder.md)

#### Throws

This function can throw errors.

#### Defined in

component.ts:114

## Properties

### eatEvent()?

> `optional` **eatEvent**: (`arg`) => `void`

This event fires when eat the food.

#### Parameters

• **arg**: `ItemComponentCompleteUseEvent`

#### Returns

`void`

#### Defined in

component.ts:117

***

### statusEffects?

> `optional` **statusEffects**: `EffectData`[]

Adds a status effect when eat the food.

#### Defined in

component.ts:116

***

### typeId

> `readonly` **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

#### Defined in

component.ts:115

## Methods

### build()

> **build**(): `void`

#### Returns

`void`

#### Defined in

component.ts:119
