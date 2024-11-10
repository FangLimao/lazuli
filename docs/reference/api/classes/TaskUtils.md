[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / TaskUtils

# Class: TaskUtils

## Constructors

### new TaskUtils()

> **new TaskUtils**(): [`TaskUtils`](TaskUtils.md)

#### Returns

[`TaskUtils`](TaskUtils.md)

## Methods

### checkCondition()

> `static` **checkCondition**(`options`, `player`, `task`): [`checkResult`](../interfaces/checkResult.md)

#### Parameters

• **options**: [`TaskUnlockCompleteOptions`](../interfaces/TaskUnlockCompleteOptions.md)

• **player**: `Player`

• **task**: [`Task`](Task.md)

#### Returns

[`checkResult`](../interfaces/checkResult.md)

#### Defined in

beta/task.ts:268

***

### generateBody()

> `static` **generateBody**(`description`, `options`): `RawMessage`

Generate the body of Task, includes descriptions, conditions, awards and tips.

#### Parameters

• **description**: `RawMessage`

• **options**: [`TaskOptions`](../interfaces/TaskOptions.md)

#### Returns

`RawMessage`

A RawMessage that includes task's descriptions, conditions, awards and tips.

#### Defined in

beta/task.ts:378

***

### getCompleteTag()

> `static` **getCompleteTag**(`task`): `string`

Get a task's complete tag.

#### Parameters

• **task**: [`Task`](Task.md)

#### Returns

`string`

The task's complete tag.

#### Defined in

beta/task.ts:250

***

### getUnlockTag()

> `static` **getUnlockTag**(`task`): `string`

Get a task's complete tag.

#### Parameters

• **task**: [`Task`](Task.md)

#### Returns

`string`

The task's complete tag.

#### Defined in

beta/task.ts:258

***

### setNameSpace()

> `static` **setNameSpace**(`str`): `void`

Set name space of the task complete tag.

#### Parameters

• **str**: `string`

#### Returns

`void`

#### Defined in

beta/task.ts:265
