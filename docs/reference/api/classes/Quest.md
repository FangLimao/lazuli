[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / Quest

# Class: Quest

Create a Quest.

## Constructors

### new Quest()

> **new Quest**(`id`, `_title`, `_body`, `options`): [`Quest`](Quest.md)

#### Parameters

• **id**: `string`

The unique id of the quest.

• **\_title**: `string` \| `RawMessage`

Title of the quest.

• **\_body**: `string` \| `RawMessage`

Body of the quest.

• **options**: [`QuestOptions`](../interfaces/QuestOptions.md)

Options of the quest.

#### Returns

[`Quest`](Quest.md)

#### Defined in

quest.ts:34

## Properties

### \_body

> `protected` **\_body**: `string` \| `RawMessage`

Body of the quest.

#### Defined in

quest.ts:37

***

### \_title

> `protected` **\_title**: `string` \| `RawMessage`

Title of the quest.

#### Defined in

quest.ts:36

***

### form

> `protected` **form**: `MessageFormData`

#### Defined in

quest.ts:26

***

### id

> `readonly` **id**: `string`

The unique id of the quest.

#### Defined in

quest.ts:35

***

### options

> **options**: [`QuestOptions`](../interfaces/QuestOptions.md)

Options of the quest.

#### Defined in

quest.ts:38

## Accessors

### body

#### Get Signature

> **get** **body**(): `string` \| `RawMessage`

##### Returns

`string` \| `RawMessage`

#### Set Signature

> **set** **body**(`content`): `void`

##### Parameters

• **content**: `string` \| `RawMessage`

##### Returns

`void`

#### Defined in

quest.ts:110

***

### title

#### Get Signature

> **get** **title**(): `string` \| `RawMessage`

##### Returns

`string` \| `RawMessage`

#### Set Signature

> **set** **title**(`content`): `void`

##### Parameters

• **content**: `string` \| `RawMessage`

##### Returns

`void`

#### Defined in

quest.ts:113

## Methods

### complete()

> **complete**(`player`): `void`

Let a player complete the quest and give award.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

quest.ts:84

***

### display()

> **display**(`player`, `backTo`?): `void`

Show form to a player.

#### Parameters

• **player**: `Player`

• **backTo?**: [`QuestBook`](QuestBook.md)

The screen player should return to after closing the form.

#### Returns

`void`

#### Defined in

quest.ts:52

***

### isCompleted()

> **isCompleted**(`player`): `boolean`

Check if a player has completed this quest.

#### Parameters

• **player**: `Player`

#### Returns

`boolean`

#### Defined in

quest.ts:99

***

### ~~register()~~

> `protected` **register**(): `void`

Registry the quest.

#### Returns

`void`

#### Deprecated

Use `Register.questRegistry()` to registry the prop

#### Defined in

quest.ts:44
