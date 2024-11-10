[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / QuestBookCategory

# Class: QuestBookCategory

Book Category for [QuestBoard](QuestBoard.md).

## Constructors

### new QuestBookCategory()

> **new QuestBookCategory**(`title`, `body`, `books`, `iconPath`?): [`QuestBookCategory`](QuestBookCategory.md)

#### Parameters

• **title**: `string` \| `RawMessage`

Title of the category.

• **body**: `string` \| `RawMessage`

Body of the category.

• **books**: [`QuestBook`](QuestBook.md)[]

The quest books that included in category.

• **iconPath?**: `string`

The icon of the category.
It should be the path from the root of the resource pack, like `texture/gui/example_pic`.

#### Returns

[`QuestBookCategory`](QuestBookCategory.md)

#### Defined in

quest.ts:287

## Properties

### body

> **body**: `string` \| `RawMessage`

Body of the category.

#### Defined in

quest.ts:289

***

### books

> **books**: [`QuestBook`](QuestBook.md)[]

The quest books that included in category.

#### Defined in

quest.ts:290

***

### iconPath?

> `optional` **iconPath**: `string`

The icon of the category.
It should be the path from the root of the resource pack, like `texture/gui/example_pic`.

#### Defined in

quest.ts:291

***

### title

> **title**: `string` \| `RawMessage`

Title of the category.

#### Defined in

quest.ts:288

## Methods

### display()

> **display**(`player`): `void`

Display the category form to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

quest.ts:297
