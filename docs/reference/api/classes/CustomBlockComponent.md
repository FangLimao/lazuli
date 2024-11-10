[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / CustomBlockComponent

# Class: CustomBlockComponent

Define a custom block component.

## Example

```ts
// Define the component
  const COMPONENT = new CustomBlockComponent("lazuli:example", {
    onEntityFallOn(arg) {
      arg.dimension.createExplosion(arg.block.location, 5);
     },
   })
  // Registry the component
  Register.componentRegistry(COMPONENT);
```

## Constructors

### new CustomBlockComponent()

> **new CustomBlockComponent**(`typeId`, `components`): [`CustomBlockComponent`](CustomBlockComponent.md)

#### Parameters

• **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

• **components**: `BlockCustomComponent`

The collection of event functions that will be called when
the event occurs on an item using this custom component id.

#### Returns

[`CustomBlockComponent`](CustomBlockComponent.md)

#### Throws

This function can throw errors.

#### Defined in

component.ts:86

## Properties

### components

> **components**: `BlockCustomComponent`

The collection of event functions that will be called when
the event occurs on an item using this custom component id.

#### Defined in

component.ts:88

***

### typeId

> `readonly` **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

#### Defined in

component.ts:87
