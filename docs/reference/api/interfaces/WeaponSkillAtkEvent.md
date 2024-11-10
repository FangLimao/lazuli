[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / WeaponSkillAtkEvent

# Interface: WeaponSkillAtkEvent

This event fires when the [WeaponAtkSkill](../classes/WeaponAtkSkill.md) is unleashed.

## Extends

- [`WeaponSkillEvent`](WeaponSkillEvent.md)

## Properties

### custom()?

> `optional` **custom**: (`attacker`, `target`?) => `void`

This custom event fires when the [WeaponSkill](../classes/WeaponSkill.md) is unleashed.

#### Parameters

• **attacker**: `Entity`

The attacker.

• **target?**: `Entity`

The target, might be undefined.

#### Returns

`void`

#### Inherited from

[`WeaponSkillEvent`](WeaponSkillEvent.md).[`custom`](WeaponSkillEvent.md#custom)

#### Defined in

item/weaponSkill.ts:50

***

### damageAtker?

> `optional` **damageAtker**: `number`

Apply damage to attacker.

#### Inherited from

[`WeaponSkillEvent`](WeaponSkillEvent.md).[`damageAtker`](WeaponSkillEvent.md#damageatker)

#### Defined in

item/weaponSkill.ts:28

***

### damageTarget?

> `optional` **damageTarget**: `number`

Apply damage to target.

#### Defined in

item/weaponSkill.ts:60

***

### effectAtker?

> `optional` **effectAtker**: `EffectData` \| `EffectData`[]

Apply effect(s) to attacker.

#### Inherited from

[`WeaponSkillEvent`](WeaponSkillEvent.md).[`effectAtker`](WeaponSkillEvent.md#effectatker)

#### Defined in

item/weaponSkill.ts:32

***

### effectTarget?

> `optional` **effectTarget**: `EffectData` \| `EffectData`[]

Apply effect(s) to target.

#### Defined in

item/weaponSkill.ts:64

***

### levels?

> `optional` **levels**: `number`

Add levels to attacker.

#### Inherited from

[`WeaponSkillEvent`](WeaponSkillEvent.md).[`levels`](WeaponSkillEvent.md#levels)

#### Defined in

item/weaponSkill.ts:40

***

### rangeEffect?

> `optional` **rangeEffect**: [`RangeEffectOptions`](RangeEffectOptions.md)

Apply effect to some entity.

#### Inherited from

[`WeaponSkillEvent`](WeaponSkillEvent.md).[`rangeEffect`](WeaponSkillEvent.md#rangeeffect)

#### Defined in

item/weaponSkill.ts:36

***

### xp?

> `optional` **xp**: `number`

Add experiences to attacker.

#### Inherited from

[`WeaponSkillEvent`](WeaponSkillEvent.md).[`xp`](WeaponSkillEvent.md#xp)

#### Defined in

item/weaponSkill.ts:44
