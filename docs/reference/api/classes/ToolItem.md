[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / ToolItem

# Class: ToolItem

Define a tool.

## Constructors

### new ToolItem()

> **new ToolItem**(`item`, `options`?): [`ToolItem`](ToolItem.md)

#### Parameters

• **item**: `ItemStack`

Item of the weapon.

• **options?**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Returns

[`ToolItem`](ToolItem.md)

#### Defined in

item/tool.ts:176

## Properties

### item

> **item**: `ItemStack`

Item of the weapon.

#### Defined in

item/tool.ts:177

***

### options?

> `optional` **options**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Defined in

item/tool.ts:178

## Methods

### listeningAxeDurability()

> **listeningAxeDurability**(): `void`

Consume durability when the tool use on logs.

#### Returns

`void`

#### Defined in

item/tool.ts:270

***

### listeningDurability()

> **listeningDurability**(): `void`

Automatically consume durability for the tools.

#### Returns

`void`

#### Defined in

item/tool.ts:191

***

### listeningHoeDurability()

> **listeningHoeDurability**(): `void`

#### Returns

`void`

#### Defined in

item/tool.ts:218

***

### listeningShovelDurability()

> **listeningShovelDurability**(): `void`

Consume durability when the tool use on dirt.

#### Returns

`void`

#### Defined in

item/tool.ts:244
