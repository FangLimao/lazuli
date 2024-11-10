[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / Boss

# Class: Boss

**`Beta`**

Define a boss entity.

## Constructors

### new Boss()

> **new Boss**(`typeId`, `skills`, `music`?, `dieEvent`?): [`Boss`](Boss.md)

**`Beta`**

#### Parameters

• **typeId**: `string`

Identifier of the type of the entity.

• **skills**: [`BossSkill`](BossSkill.md)[]

The [BossSkill](BossSkill.md) the boss own.

• **music?**: [`BossMusicOptions`](../interfaces/BossMusicOptions.md)

The music to play when boss is spawned.

• **dieEvent?**

Trigger event when the boss die.

#### Returns

[`Boss`](Boss.md)

#### Defined in

entity/boss.ts:16

## Properties

### dieEvent()?

> `optional` **dieEvent**: (`arg`) => `void`

Trigger event when the boss die.

#### Parameters

• **arg**: `EntityDieAfterEvent`

#### Returns

`void`

#### Defined in

entity/boss.ts:20

***

### music?

> `optional` **music**: [`BossMusicOptions`](../interfaces/BossMusicOptions.md)

**`Beta`**

The music to play when boss is spawned.

#### Defined in

entity/boss.ts:19

***

### skills

> **skills**: [`BossSkill`](BossSkill.md)[]

**`Beta`**

The [BossSkill](BossSkill.md) the boss own.

#### Defined in

entity/boss.ts:18

***

### typeId

> **typeId**: `string`

**`Beta`**

Identifier of the type of the entity.

#### Defined in

entity/boss.ts:17

## Methods

### playMusic()

> **playMusic**(`player`): `void`

**`Beta`**

#### Parameters

• **player**: `Player` \| `Player`[]

#### Returns

`void`

#### Defined in

entity/boss.ts:26

***

### unleashSkill()

> **unleashSkill**(`entity`, `boss`): `void`

**`Beta`**

#### Parameters

• **entity**: `Entity`

• **boss**: `Entity`

#### Returns

`void`

#### Defined in

entity/boss.ts:40
