[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / SkillEffect

# Interface: SkillEffect

Unleash effect of boss skill.

## Properties

### damage?

> `optional` **damage**: `number`

Apply damage when skill unleash.

#### Defined in

entity/bossSkill.ts:73

***

### event()?

> `optional` **event**: (`entity`, `boss`?) => `void`

The trigger effect when skill unleash.

#### Parameters

• **entity**: `Entity`

• **boss?**: `Entity`

#### Returns

`void`

#### Defined in

entity/bossSkill.ts:61

***

### exp?

> `optional` **exp**: `number`

Add exp when skill unleash.

#### Defined in

entity/bossSkill.ts:65

***

### level?

> `optional` **level**: `number`

Add level when skill unleash.

#### Defined in

entity/bossSkill.ts:69
