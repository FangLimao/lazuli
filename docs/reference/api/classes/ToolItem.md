[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / ToolItem

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

item/tool.ts:169

## Properties

### item

> **item**: `ItemStack`

Item of the weapon.

#### Defined in

item/tool.ts:170

***

### options?

> `optional` **options**: [`ToolOptions`](../interfaces/ToolOptions.md)

Additional options of the tool.

#### Defined in

item/tool.ts:171

## Methods

### listeningAxeDurability()

> **listeningAxeDurability**(): `void`

Consume durability when the tool use on logs.

#### Returns

`void`

#### Defined in

item/tool.ts:263

***

### listeningDurability()

> **listeningDurability**(): `void`

Automatically consume durability for the tools.

#### Returns

`void`

#### Defined in

item/tool.ts:184

***

### listeningHoeDurability()

> **listeningHoeDurability**(): `void`

#### Returns

`void`

#### Defined in

item/tool.ts:211

***

### listeningShovelDurability()

> **listeningShovelDurability**(): `void`

Consume durability when the tool use on dirt.

#### Returns

`void`

#### Defined in

item/tool.ts:237
