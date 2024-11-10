[**@lazuli/logger v2.2.0**](../README.md) • **Docs**

***

[@lazuli/logger v2.2.0](../globals.md) / LoggerManager

# Class: LoggerManager

## Methods

### debug()

> **debug**(`message`, `players`?): `void`

Log with [LogLevel.DEBUG](../enumerations/LogLevel.md#debug)

#### Parameters

• **message**: `string`

• **players?**: `Player`[]

#### Returns

`void`

#### Defined in

index.ts:115

***

### error()

> **error**(`message`, `players`?): `void`

Same as console.error.

#### Parameters

• **message**: `string`

• **players?**: `Player`[]

the players that would receive stack trace.

#### Returns

`void`

#### Defined in

index.ts:165

***

### fatal()

> **fatal**(`message`): `void`

Same as `error()`, but the stack trace will be sent to all players

#### Parameters

• **message**: `string`

#### Returns

`void`

#### Defined in

index.ts:180

***

### getLogLevel()

> **getLogLevel**(`player`?): [`LogLevel`](../enumerations/LogLevel.md)

Get player(or the world)'s LogLevel.

#### Parameters

• **player?**: `Player`

#### Returns

[`LogLevel`](../enumerations/LogLevel.md)

#### Defined in

index.ts:96

***

### info()

> **info**(`message`, `players`?): `void`

Log with [LogLevel.INFO](../enumerations/LogLevel.md#info)
The message will be sent to world if no players are given.

#### Parameters

• **message**: `string`

• **players?**: `Player`[]

#### Returns

`void`

#### Defined in

index.ts:132

***

### log()

> **log**(`message`, `players`?): `void`

The `log()` function is an alias for [info](LoggerManager.md#info).

#### Parameters

• **message**: `string`

• **players?**: `Player`[]

#### Returns

`void`

#### Defined in

index.ts:107

***

### setLogLevel()

> **setLogLevel**(`level`, `player`?): `void`

Set player(or the world)'s LogLevel.

#### Parameters

• **level**: [`LogLevel`](../enumerations/LogLevel.md)

• **player?**: `Player`

#### Returns

`void`

#### Defined in

index.ts:85

***

### warn()

> **warn**(`message`, `players`?): `void`

Same as console.warn.

#### Parameters

• **message**: `string`

• **players?**: `Player`[]

the players that would receive stack trace.

#### Returns

`void`

#### Defined in

index.ts:148

***

### getLogger()

> `static` **getLogger**(`id`?, `feedback`?): [`LoggerManager`](LoggerManager.md)

Get a new Logger

#### Parameters

• **id?**: `string`

if it's not set, the value will be te result of the `getModName()`.

• **feedback?**: `string`

the info which will be sent when an error or a fatal error.

#### Returns

[`LoggerManager`](LoggerManager.md)

#### Defined in

index.ts:77
