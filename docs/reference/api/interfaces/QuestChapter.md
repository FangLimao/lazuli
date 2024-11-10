[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / QuestChapter

# Interface: QuestChapter

Chapters of a quest book.

## Properties

### body

> **body**: `string` \| `RawMessage`

Body of the chapter.

#### Defined in

quest.ts:575

***

### iconPath?

> `optional` **iconPath**: `string`

The icon of the Chapter.
It should be the path from the root of the resource pack.

#### Example

```ts
texture/gui/example_pic
```

#### Defined in

quest.ts:585

***

### quests

> **quests**: [`Quest`](../classes/Quest.md)[]

Quests of the chapter.

#### Defined in

quest.ts:579

***

### title

> **title**: `string` \| `RawMessage`

Title of the chapter.

#### Defined in

quest.ts:571
