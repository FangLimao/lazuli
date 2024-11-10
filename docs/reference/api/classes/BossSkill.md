[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / BossSkill

# Class: BossSkill

Define a boss skill.

## Constructors

### new BossSkill()

> **new BossSkill**(`id`, `cooldownTime`, `radius`, `effect`, `message`?): [`BossSkill`](BossSkill.md)

#### Parameters

• **id**: `string`

Boss skill`s id.

• **cooldownTime**: `number`

Cooldown time of the boss skill.

• **radius**: `number`

The radius within which entity can be effected by the skill.

• **effect**: [`SkillEffect`](../interfaces/SkillEffect.md)

This event fires when the skill is triggered.

• **message?**: `string` \| `RawMessage`

Message to send when the skill is unleashed.

#### Returns

[`BossSkill`](BossSkill.md)

#### Defined in

entity/bossSkill.ts:14

## Properties

### cooldownTime

> **cooldownTime**: `number`

Cooldown time of the boss skill.

#### Defined in

entity/bossSkill.ts:16

***

### effect

> **effect**: [`SkillEffect`](../interfaces/SkillEffect.md)

This event fires when the skill is triggered.

#### Defined in

entity/bossSkill.ts:18

***

### id

> **id**: `string`

Boss skill`s id.

#### Defined in

entity/bossSkill.ts:15

***

### message?

> `optional` **message**: `string` \| `RawMessage`

Message to send when the skill is unleashed.

#### Defined in

entity/bossSkill.ts:19

***

### radius

> **radius**: `number`

The radius within which entity can be effected by the skill.

#### Defined in

entity/bossSkill.ts:17

## Methods

### unleash()

> **unleash**(`entity`, `boss`?): `void`

Unleash the skill to an entity.

#### Parameters

• **entity**: `Entity`

• **boss?**: `Entity`

#### Returns

`void`

#### Defined in

entity/bossSkill.ts:26

***

### unleashArray()

> **unleashArray**(`entities`, `boss`?): `void`

Unleash the skill to entities.

#### Parameters

• **entities**: `Entity`[]

Entities to unleash.

• **boss?**: `Entity`

The boss itself.

#### Returns

`void`

#### Defined in

entity/bossSkill.ts:43
