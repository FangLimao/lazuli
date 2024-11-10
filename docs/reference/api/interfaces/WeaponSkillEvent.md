[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / WeaponSkillEvent

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

item/weaponSkill.ts:45

***

### damageAtker?

> `optional` **damageAtker**: `number`

Apply damage to attacker.

#### Defined in

item/weaponSkill.ts:23

***

### effectAtker?

> `optional` **effectAtker**: `EffectData` \| `EffectData`[]

Apply effect(s) to attacker.

#### Defined in

item/weaponSkill.ts:27

***

### levels?

> `optional` **levels**: `number`

Add levels to attacker.

#### Defined in

item/weaponSkill.ts:35

***

### rangeEffect?

> `optional` **rangeEffect**: [`RangeEffectOptions`](RangeEffectOptions.md)

Apply effect to some entity.

#### Defined in

item/weaponSkill.ts:31

***

### xp?

> `optional` **xp**: `number`

Add experiences to attacker.

#### Defined in

item/weaponSkill.ts:39
