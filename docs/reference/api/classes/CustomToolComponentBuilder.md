[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / CustomToolComponentBuilder

# Class: CustomToolComponentBuilder

Build a custom tool component.

## Example

```ts
new CustomToolComponentBuilder("ldk:example_component",{
    type: "axe"
}).build();
```

## Constructors

### new CustomToolComponentBuilder()

> **new CustomToolComponentBuilder**(`typeId`, `options`?): [`CustomToolComponentBuilder`](CustomToolComponentBuilder.md)

#### Parameters

• **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

• **options?**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Returns

[`CustomToolComponentBuilder`](CustomToolComponentBuilder.md)

#### Defined in

component.ts:154

## Properties

### options?

> `optional` **options**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Defined in

component.ts:156

***

### typeId

> `readonly` **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

#### Defined in

component.ts:155

## Methods

### build()

> **build**(): `void`

#### Returns

`void`

#### Defined in

component.ts:158
