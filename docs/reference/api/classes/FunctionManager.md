[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / FunctionManager

# Class: FunctionManager

Manager for functions.

## Constructors

### new FunctionManager()

> **new FunctionManager**(): [`FunctionManager`](FunctionManager.md)

#### Returns

[`FunctionManager`](FunctionManager.md)

## Methods

### chatTrigger()

> `static` **chatTrigger**(`path`, `msg`): `void`

Run function when a chat message has been broadcast or sent to players.

#### Parameters

• **path**: `string`

The function's path.

• **msg**: `string`

Message that trigger run function

#### Returns

`void`

#### Defined in

function.ts:36

***

### playerLeaveTrigger()

> `static` **playerLeaveTrigger**(`path`): `void`

Run function when the player leave.

#### Parameters

• **path**: `string`

The function's path.

#### Returns

`void`

#### Defined in

function.ts:26

***

### playerSpawnTrigger()

> `static` **playerSpawnTrigger**(`path`, `initialSpawn`): `void`

Run function when the player spawn.

#### Parameters

• **path**: `string`

The function's path.

• **initialSpawn**: `boolean` = `false`

If true, the function will only run on player's initial spawn.

#### Returns

`void`

#### Defined in

function.ts:12
