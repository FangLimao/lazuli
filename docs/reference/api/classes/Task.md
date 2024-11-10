[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / Task

# Class: Task

Create a task.

## Catetory

Need Registry

## Constructors

### new Task()

> **new Task**(`id`, `_title`, `_body`, `options`): [`Task`](Task.md)

#### Parameters

• **id**: `string`

The unique id of the task.

• **\_title**: `RawMessage`

Title of the task, only support RawMessage.

• **\_body**: `RawMessage`

Body of the task, only support RawMessage.

• **options**: [`TaskOptions`](../interfaces/TaskOptions.md)

Options of the task.

*You MUST assign the complete condition and the award, others are optional.*

#### Returns

[`Task`](Task.md)

#### Defined in

beta/task.ts:20

## Properties

### \_body

> **\_body**: `RawMessage`

Body of the task, only support RawMessage.

#### Defined in

beta/task.ts:32

***

### \_title

> **\_title**: `RawMessage`

Title of the task, only support RawMessage.

#### Defined in

beta/task.ts:28

***

### id

> `readonly` **id**: `string`

The unique id of the task.

#### Defined in

beta/task.ts:24

***

### options

> **options**: [`TaskOptions`](../interfaces/TaskOptions.md)

Options of the task.

*You MUST assign the complete condition and the award, others are optional.*

#### Defined in

beta/task.ts:38

## Accessors

### body

#### Get Signature

> **get** **body**(): `RawMessage`

##### Returns

`RawMessage`

#### Set Signature

> **set** **body**(`content`): `void`

##### Parameters

• **content**: `RawMessage`

##### Returns

`void`

#### Defined in

beta/task.ts:169

***

### title

#### Get Signature

> **get** **title**(): `RawMessage`

##### Returns

`RawMessage`

#### Set Signature

> **set** **title**(`content`): `void`

##### Parameters

• **content**: `RawMessage`

##### Returns

`void`

#### Defined in

beta/task.ts:172

## Methods

### complete()

> **complete**(`player`): `void`

Let a player complete the task and give award.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

beta/task.ts:119

***

### display()

> **display**(`player`, `backTo`?): `void`

Display ui form to the player.

#### Parameters

• **player**: `Player`

• **backTo?**: [`TaskList`](TaskList.md) \| [`TaskCategory`](TaskCategory.md)

The screen that player should return to after closing the form.

#### Returns

`void`

#### Defined in

beta/task.ts:101

***

### displayFail()

> `protected` **displayFail**(`player`, `backTo`?): `void`

#### Parameters

• **player**: `Player`

• **backTo?**: [`TaskList`](TaskList.md) \| [`TaskCategory`](TaskCategory.md)

#### Returns

`void`

#### Defined in

beta/task.ts:87

***

### displayInfo()

> `protected` **displayInfo**(`player`, `backTo`?): `void`

#### Parameters

• **player**: `Player`

• **backTo?**: [`TaskList`](TaskList.md) \| [`TaskCategory`](TaskCategory.md)

The screen that player should return to after closing the form.

#### Returns

`void`

#### Defined in

beta/task.ts:49

***

### isCompleted()

> **isCompleted**(`player`): `boolean`

Check if the player has the complete tag.

#### Parameters

• **player**: `Player`

#### Returns

`boolean`

#### Defined in

beta/task.ts:148

***

### isUnlocked()

> **isUnlocked**(`player`): `boolean`

Check if the player has the unlock tag.

#### Parameters

• **player**: `Player`

#### Returns

`boolean`

#### Defined in

beta/task.ts:155

***

### unlock()

> **unlock**(`player`): `void`

Let a player complete the task and give award.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

beta/task.ts:138
