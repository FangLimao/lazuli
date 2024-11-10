[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / QuestChapter

# Interface: QuestChapter

Chapters of a quest book.

## Properties

### body

> **body**: `string` \| `RawMessage`

Body of the chapter.

#### Defined in

quest.ts:568

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

quest.ts:578

***

### quests

> **quests**: [`Quest`](../classes/Quest.md)[]

Quests of the chapter.

#### Defined in

quest.ts:572

***

### title

> **title**: `string` \| `RawMessage`

Title of the chapter.

#### Defined in

quest.ts:564
