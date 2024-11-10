[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / TaskCategory

# Class: TaskCategory

## Constructors

### new TaskCategory()

> **new TaskCategory**(`title`, `body`, `items`, `iconPath`?): [`TaskCategory`](TaskCategory.md)

#### Parameters

• **title**: `RawMessage`

• **body**: `RawMessage`

• **items**: [`Task`](Task.md)[]

• **iconPath?**: `string`

#### Returns

[`TaskCategory`](TaskCategory.md)

#### Defined in

beta/task.ts:178

## Properties

### body

> **body**: `RawMessage`

#### Defined in

beta/task.ts:180

***

### iconPath?

> `optional` **iconPath**: `string`

#### Defined in

beta/task.ts:182

***

### items

> **items**: [`Task`](Task.md)[]

#### Defined in

beta/task.ts:181

***

### title

> **title**: `RawMessage`

#### Defined in

beta/task.ts:179

## Methods

### display()

> **display**(`player`, `backTo`?): `void`

Display ui form to the player.

#### Parameters

• **player**: `Player`

• **backTo?**: [`TaskList`](TaskList.md)

The screen that player should return to after closing the form.

#### Returns

`void`

#### Defined in

beta/task.ts:189

***

### isCompleted()

> **isCompleted**(`player`): `boolean`

Returns whether the player has completed all tasks in the category.

#### Parameters

• **player**: `Player`

#### Returns

`boolean`

Whether the player has completed all tasks in the category.

#### Defined in

beta/task.ts:211
