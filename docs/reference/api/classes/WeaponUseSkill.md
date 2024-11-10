[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / WeaponUseSkill

# Class: WeaponUseSkill

Define a weapon attack skill without trigger.
Please use [WeaponAtkSkill](WeaponAtkSkill.md) or [WeaponUseSkill](WeaponUseSkill.md).

## Extends

- [`WeaponSkill`](WeaponSkill.md)

## Constructors

### new WeaponUseSkill()

> **new WeaponUseSkill**(`weight`, `event`, `actionBarTips`?, `durability`?): [`WeaponUseSkill`](WeaponUseSkill.md)

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

[`WeaponUseSkill`](WeaponUseSkill.md)

#### Overrides

[`WeaponSkill`](WeaponSkill.md).[`constructor`](WeaponSkill.md#constructors)

#### Defined in

item/weaponSkill.ts:205

## Properties

### actionBarTips?

> `optional` **actionBarTips**: `RawMessage`

Tips on action bar when this skill is triggered.

#### Inherited from

[`WeaponSkill`](WeaponSkill.md).[`actionBarTips`](WeaponSkill.md#actionbartips)

#### Defined in

item/weaponSkill.ts:208

***

### durability?

> `optional` **durability**: `number`

The amount of durability consumed when unleashing this skill.

#### Inherited from

[`WeaponSkill`](WeaponSkill.md).[`durability`](WeaponSkill.md#durability)

#### Defined in

item/weaponSkill.ts:209

***

### event

> **event**: `"empty"` \| [`WeaponSkillEvent`](../interfaces/WeaponSkillEvent.md)

This event fires when the skill is triggered.

#### Inherited from

[`WeaponSkill`](WeaponSkill.md).[`event`](WeaponSkill.md#event)

#### Defined in

item/weaponSkill.ts:207

***

### weight

> **weight**: `number`

The probability to triggered when multiple skills are added to a weapon.

#### Inherited from

[`WeaponSkill`](WeaponSkill.md).[`weight`](WeaponSkill.md#weight)

#### Defined in

item/weaponSkill.ts:206

## Methods

### getSkillType()

> **getSkillType**(): [`WeaponSkillType`](../type-aliases/WeaponSkillType.md)

Get the skill`s type.
@return Type to the skill, such as `"none"`, `"attack"` or `"use"`.

#### Returns

[`WeaponSkillType`](../type-aliases/WeaponSkillType.md)

#### Overrides

[`WeaponSkill`](WeaponSkill.md).[`getSkillType`](WeaponSkill.md#getskilltype)

#### Defined in

item/weaponSkill.ts:217

***

### unleash()

> **unleash**(`attacker`, `target`?): `void`

Unleash the weapon skill.

#### Parameters

• **attacker**: `Entity`

• **target?**: `Entity`

#### Returns

`void`

#### Inherited from

[`WeaponSkill`](WeaponSkill.md).[`unleash`](WeaponSkill.md#unleash)

#### Defined in

item/weaponSkill.ts:135
