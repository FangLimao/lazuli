[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / QuestBoard

# Class: QuestBoard

## Constructors

### new QuestBoard()

> **new QuestBoard**(`id`, `title`, `body`, `books`, `displayCondition`): [`QuestBoard`](QuestBoard.md)

#### Parameters

• **id**: `string`

The unique id of the board.

• **title**: `string` \| `RawMessage`

Title of the board.

• **body**: `string` \| `RawMessage`

Body of the board.

• **books**: ([`QuestBook`](QuestBook.md) \| [`QuestBookCategory`](QuestBookCategory.md))[]

Books of the board.

• **displayCondition**: `DisplayCondition`

Control when collection is displayed.

#### Returns

[`QuestBoard`](QuestBoard.md)

#### Defined in

quest.ts:319

## Properties

### body

> `protected` **body**: `string` \| `RawMessage`

Body of the board.

#### Defined in

quest.ts:322

***

### books

> **books**: ([`QuestBook`](QuestBook.md) \| [`QuestBookCategory`](QuestBookCategory.md))[]

Books of the board.

#### Defined in

quest.ts:323

***

### displayCondition

> **displayCondition**: `DisplayCondition`

Control when collection is displayed.

#### Defined in

quest.ts:324

***

### id

> `readonly` **id**: `string`

The unique id of the board.

#### Defined in

quest.ts:320

***

### title

> `protected` **title**: `string` \| `RawMessage`

Title of the board.

#### Defined in

quest.ts:321

## Methods

### display()

> **display**(`player`): `void`

Display the board form to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

quest.ts:331
