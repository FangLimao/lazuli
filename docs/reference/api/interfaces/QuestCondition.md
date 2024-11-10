[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / QuestCondition

# Interface: QuestCondition

Conditions of a quest.

## Properties

### item?

> `optional` **item**: `ItemData`

Match only typeId and min amount.

#### Defined in

quest.ts:595

***

### killEntity?

> `optional` **killEntity**: `EntityData`

The specific entity will be required to unlock the quest.

#### Defined in

quest.ts:607

***

### playerXpLevel?

> `optional` **playerXpLevel**: `number`

The specific level will be required to unlock the quest.

#### Defined in

quest.ts:599

***

### playerXpPoint?

> `optional` **playerXpPoint**: `number`

The specific point will be required to unlock the quest.

#### Defined in

quest.ts:603

***

### quests?

> `optional` **quests**: [`Quest`](../classes/Quest.md)[]

The specific quests will be required to unlock the quest.

#### Defined in

quest.ts:611
