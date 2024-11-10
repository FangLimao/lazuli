[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / FormManager

# Class: FormManager

A manager of server-ui form.

## Constructors

### new FormManager()

> **new FormManager**(): [`FormManager`](FormManager.md)

#### Returns

[`FormManager`](FormManager.md)

## Methods

### alert()

> `static` **alert**(`message`, `player`): `void`

#### Parameters

• **message**: `string` \| `RawMessage`

• **player**: `Player` \| `Player`[]

#### Returns

`void`

#### Defined in

ui.ts:8

***

### confirm()

> `static` **confirm**(`message`, `player`): `void`

#### Parameters

• **message**: `string` \| `RawMessage`

• **player**: `Player`

#### Returns

`void`

#### Defined in

ui.ts:11

***

### prompt()

> `static` **prompt**(`message`, `placeholderText`, `player`, `defaultText`?): `void`

#### Parameters

• **message**: `string` \| `RawMessage`

• **placeholderText**: `string` \| `RawMessage`

• **player**: `Player`

• **defaultText?**: `string`

#### Returns

`void`

#### Defined in

ui.ts:14
