[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / CustomItemComponent

# Class: CustomItemComponent

Define a custom item component.

## Example

```ts
// Define the component
 const COMPONENT = new CustomItemComponent("lazuli:example", {
    onConsume(arg) {
      arg.source.addEffect("posion", 200);
    },
  })
  // Registry the component
  Register.componentRegistry(COMPONENT);
```

## Constructors

### new CustomItemComponent()

> **new CustomItemComponent**(`typeId`, `components`): [`CustomItemComponent`](CustomItemComponent.md)

#### Parameters

• **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the 'minecraft:custom_components' item
component.

• **components**: `ItemCustomComponent`

The collection of event functions that will be called when
the event occurs on an item using this custom component id.

#### Returns

[`CustomItemComponent`](CustomItemComponent.md)

#### Throws

This function can throw errors.

#### Defined in

component.ts:35

## Properties

### components

> **components**: `ItemCustomComponent`

The collection of event functions that will be called when
the event occurs on an item using this custom component id.

#### Defined in

component.ts:37

***

### typeId

> `readonly` **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the 'minecraft:custom_components' item
component.

#### Defined in

component.ts:36
