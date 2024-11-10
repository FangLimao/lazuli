[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / ToolTag

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

item/tool.ts:62

## Properties

### options?

> `optional` **options**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Defined in

item/tool.ts:64

***

### tag

> **tag**: `string`

The tool tag.

#### Defined in

item/tool.ts:63

## Methods

### listeningAxeDurability()

> **listeningAxeDurability**(): `void`

Consume durability when the tool use on logs.

#### Returns

`void`

#### Defined in

item/tool.ts:145

***

### listeningDurability()

> **listeningDurability**(): `void`

Automatically consume durability for the tools.

#### Returns

`void`

#### Defined in

item/tool.ts:69

***

### listeningHoeDurability()

> **listeningHoeDurability**(): `void`

#### Returns

`void`

#### Defined in

item/tool.ts:122

***

### listeningShovelDurability()

> **listeningShovelDurability**(): `void`

Consume durability when the tool use on dirt.

#### Returns

`void`

#### Defined in

item/tool.ts:99
