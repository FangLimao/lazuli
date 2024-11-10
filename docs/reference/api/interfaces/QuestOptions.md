[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / QuestOptions

# Interface: QuestOptions

Options of a quest.

## Properties

### award

> **award**: [`QuestAward`](QuestAward.md)

It will be called when the Quest is completed by the player.

#### Defined in

quest.ts:643

***

### condition

> **condition**: [`QuestCondition`](QuestCondition.md)

Condition to complete the quest.

#### Defined in

quest.ts:639

***

### iconPath?

> `optional` **iconPath**: `string`

The icon of the Quest.
It should be the path from the root of the resource pack.

#### Example

```ts
texture/gui/example_pic
```

#### Defined in

quest.ts:653

***

### tips?

> `optional` **tips**: `string` \| `RawMessage`

Tips of the quest.

#### Defined in

quest.ts:647
