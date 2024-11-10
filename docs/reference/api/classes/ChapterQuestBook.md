[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / ChapterQuestBook

# Class: ChapterQuestBook

Create a Quest Book with Chapters.

## Constructors

### new ChapterQuestBook()

> **new ChapterQuestBook**(`id`, `title`, `body`, `chapters`, `iconPath`?): [`ChapterQuestBook`](ChapterQuestBook.md)

#### Parameters

• **id**: `string`

The unique id of the quest book.

• **title**: `string` \| `RawMessage`

Title of the quest book.

• **body**: `string` \| `RawMessage`

Body of the quest book.

• **chapters**: [`QuestChapter`](../interfaces/QuestChapter.md)[]

Chapters of the quest book.

• **iconPath?**: `string`

The icon of the book.
It should be the path from the root of the resource pack, like `texture/gui/example_pic`

#### Returns

[`ChapterQuestBook`](ChapterQuestBook.md)

#### Defined in

quest.ts:208

## Properties

### body

> `protected` **body**: `string` \| `RawMessage`

Body of the quest book.

#### Defined in

quest.ts:211

***

### chapters

> **chapters**: [`QuestChapter`](../interfaces/QuestChapter.md)[]

Chapters of the quest book.

#### Defined in

quest.ts:212

***

### iconPath?

> `optional` **iconPath**: `string`

The icon of the book.
It should be the path from the root of the resource pack, like `texture/gui/example_pic`

#### Defined in

quest.ts:213

***

### id

> `readonly` **id**: `string`

The unique id of the quest book.

#### Defined in

quest.ts:209

***

### title

> `protected` **title**: `string` \| `RawMessage`

Title of the quest book.

#### Defined in

quest.ts:210

## Methods

### display()

> **display**(`player`): `void`

Display the book to the player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

quest.ts:226

***

### ~~register()~~

> `protected` **register**(): `void`

Registry the prop.

#### Returns

`void`

#### Deprecated

Use `Register.questRegistry()` to registry the prop

#### Defined in

quest.ts:219
