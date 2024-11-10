[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / ToolTag

# Class: ToolTag

Define a tool tag.

## Constructors

### new ToolTag()

> **new ToolTag**(`tag`, `options`?): [`ToolTag`](ToolTag.md)

#### Parameters

• **tag**: `string`

The tool tag.

• **options?**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Returns

[`ToolTag`](ToolTag.md)

#### Defined in

item/tool.ts:55

## Properties

### options?

> `optional` **options**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Defined in

item/tool.ts:57

***

### tag

> **tag**: `string`

The tool tag.

#### Defined in

item/tool.ts:56

## Methods

### listeningAxeDurability()

> **listeningAxeDurability**(): `void`

Consume durability when the tool use on logs.

#### Returns

`void`

#### Defined in

item/tool.ts:138

***

### listeningDurability()

> **listeningDurability**(): `void`

Automatically consume durability for the tools.

#### Returns

`void`

#### Defined in

item/tool.ts:62

***

### listeningHoeDurability()

> **listeningHoeDurability**(): `void`

#### Returns

`void`

#### Defined in

item/tool.ts:115

***

### listeningShovelDurability()

> **listeningShovelDurability**(): `void`

Consume durability when the tool use on dirt.

#### Returns

`void`

#### Defined in

item/tool.ts:92
