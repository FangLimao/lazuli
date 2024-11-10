[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / WeaponSkill

# Class: WeaponSkill

Define a weapon attack skill without trigger.
Please use [WeaponAtkSkill](WeaponAtkSkill.md) or [WeaponUseSkill](WeaponUseSkill.md).

## Extended by

- [`WeaponAtkSkill`](WeaponAtkSkill.md)
- [`WeaponUseSkill`](WeaponUseSkill.md)

## Constructors

### new WeaponSkill()

> **new WeaponSkill**(`weight`, `event`, `actionBarTips`?, `durability`?): [`WeaponSkill`](WeaponSkill.md)

#### Parameters

• **weight**: `number`

The probability to triggered when multiple skills are added to a weapon.

• **event**: `"empty"` \| [`WeaponSkillEvent`](../interfaces/WeaponSkillEvent.md)

This event fires when the skill is triggered.

• **actionBarTips?**: `RawMessage`

Tips on action bar when this skill is triggered.

• **durability?**: `number`

The amount of durability consumed when unleashing this skill.

#### Returns

[`WeaponSkill`](WeaponSkill.md)

#### Defined in

item/weaponSkill.ts:119

## Properties

### actionBarTips?

> `optional` **actionBarTips**: `RawMessage`

Tips on action bar when this skill is triggered.

#### Defined in

item/weaponSkill.ts:122

***

### durability?

> `optional` **durability**: `number`

The amount of durability consumed when unleashing this skill.

#### Defined in

item/weaponSkill.ts:123

***

### event

> **event**: `"empty"` \| [`WeaponSkillEvent`](../interfaces/WeaponSkillEvent.md)

This event fires when the skill is triggered.

#### Defined in

item/weaponSkill.ts:121

***

### weight

> **weight**: `number`

The probability to triggered when multiple skills are added to a weapon.

#### Defined in

item/weaponSkill.ts:120

## Methods

### getSkillType()

> **getSkillType**(): [`WeaponSkillType`](../type-aliases/WeaponSkillType.md)

Get the skill`s type.
@return Type to the skill, such as `"none"`, `"attack"` or `"use"`.

#### Returns

[`WeaponSkillType`](../type-aliases/WeaponSkillType.md)

#### Defined in

item/weaponSkill.ts:143

***

### unleash()

> **unleash**(`attacker`, `target`?): `void`

Unleash the weapon skill.

#### Parameters

• **attacker**: `Entity`

• **target?**: `Entity`

#### Returns

`void`

#### Defined in

item/weaponSkill.ts:130
