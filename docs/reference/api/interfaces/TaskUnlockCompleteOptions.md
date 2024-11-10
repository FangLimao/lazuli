[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / TaskUnlockCompleteOptions

# Interface: TaskUnlockCompleteOptions

Contidions that control when unlock or complete the task.

**NOTE: If specify more than one condition, the task will be unlocked when any condition is achieved, but it will be completed after all conditions are achieved.**

## Properties

### exp?

> `optional` **exp**: `number`

The specific point will be required to unlock the task.

#### Defined in

beta/task.ts:500

***

### item?

> `optional` **item**: `ItemData`

Unlock the task when player has the specific item(s).

#### Defined in

beta/task.ts:488

***

### killEntity?

> `optional` **killEntity**: `EntityData`

The specific entity will be required to unlock the task.

#### Defined in

beta/task.ts:492

***

### level?

> `optional` **level**: `number`

The specific level will be required to unlock the task.

#### Defined in

beta/task.ts:496

***

### tasks?

> `optional` **tasks**: [`Task`](../classes/Task.md)[]

The specific tasks will be required to unlock the task.

#### Defined in

beta/task.ts:504
