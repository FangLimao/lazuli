[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / QuestBook

# Class: QuestBook

Create a quest book.

## Constructors

### new QuestBook()

> **new QuestBook**(`id`, `title`, `body`, `options`, `iconPath`?): [`QuestBook`](QuestBook.md)

#### Parameters

• **id**: `string`

The unique id of the quest book.

• **title**: `string` \| `RawMessage`

Title of the quest book.

• **body**: `string` \| `RawMessage`

Body of the quest book.

• **options**: [`QuestBookOptions`](../interfaces/QuestBookOptions.md)

Options of the quest book.

• **iconPath?**: `string`

The icon of the book.
It should be the path from the root of the resource pack, like `texture/gui/example_pic`

#### Returns

[`QuestBook`](QuestBook.md)

#### Defined in

quest.ts:127

## Properties

### body

> **body**: `string` \| `RawMessage`

Body of the quest book.

#### Defined in

quest.ts:130

***

### iconPath?

> `optional` **iconPath**: `string`

The icon of the book.
It should be the path from the root of the resource pack, like `texture/gui/example_pic`

#### Defined in

quest.ts:132

***

### id

> `readonly` **id**: `string`

The unique id of the quest book.

#### Defined in

quest.ts:128

***

### options

> **options**: [`QuestBookOptions`](../interfaces/QuestBookOptions.md)

Options of the quest book.

#### Defined in

quest.ts:131

***

### title

> **title**: `string` \| `RawMessage`

Title of the quest book.

#### Defined in

quest.ts:129

## Methods

### addQuest()

> **addQuest**(`quest`, `message`?): `void`

Add a quest.

#### Parameters

• **quest**: [`Quest`](Quest.md)

• **message?**: `string` \| `RawMessage`

Optional information will be sent to world.

#### Returns

`void`

#### Defined in

quest.ts:168

***

### display()

> **display**(`player`, `backTo`?): `void`

Display the book to the player.

#### Parameters

• **player**: `Player`

• **backTo?**: [`QuestBoard`](QuestBoard.md) \| [`QuestBookCategory`](QuestBookCategory.md)

The screen player should return to after closing the form.

#### Returns

`void`

#### Defined in

quest.ts:146

***

### getQuest()

> **getQuest**(`id`): `undefined` \| [`Quest`](Quest.md)

Get the quest by id.

#### Parameters

• **id**: `string`

#### Returns

`undefined` \| [`Quest`](Quest.md)

#### Defined in

quest.ts:178

***

### getQuests()

> **getQuests**(): [`Quest`](Quest.md)[]

Get all quests.

#### Returns

[`Quest`](Quest.md)[]

#### Defined in

quest.ts:184

***

### ~~register()~~

> `protected` **register**(): `void`

Registry the prop.

#### Returns

`void`

#### Deprecated

Use `Register.questRegistry()` to registry the prop

#### Defined in

quest.ts:138