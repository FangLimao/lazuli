[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / WeaponSkillEvent

# Interface: WeaponSkillEvent

This event fires when the [WeaponSkill](../classes/WeaponSkill.md) is unleashed.

## Extended by

- [`WeaponSkillAtkEvent`](WeaponSkillAtkEvent.md)

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

#### Defined in

item/weaponSkill.ts:50

***

### damageAtker?

> `optional` **damageAtker**: `number`

Apply damage to attacker.

#### Defined in

item/weaponSkill.ts:28

***

### effectAtker?

> `optional` **effectAtker**: `EffectData` \| `EffectData`[]

Apply effect(s) to attacker.

#### Defined in

item/weaponSkill.ts:32

***

### levels?

> `optional` **levels**: `number`

Add levels to attacker.

#### Defined in

item/weaponSkill.ts:40

***

### rangeEffect?

> `optional` **rangeEffect**: [`RangeEffectOptions`](RangeEffectOptions.md)

Apply effect to some entity.

#### Defined in

item/weaponSkill.ts:36

***

### xp?

> `optional` **xp**: `number`

Add experiences to attacker.

#### Defined in

item/weaponSkill.ts:44
