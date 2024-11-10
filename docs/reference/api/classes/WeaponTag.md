[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / WeaponTag

# Class: WeaponTag

Define a tool tag.

## Constructors

### new WeaponTag()

> **new WeaponTag**(`tag`, `options`?): [`WeaponTag`](WeaponTag.md)

#### Parameters

• **tag**: `string`

The weapon tag.

• **options?**: [`WeaponOptions`](../interfaces/WeaponOptions.md)

Additional options of the weapon.

#### Returns

[`WeaponTag`](WeaponTag.md)

#### Defined in

item/weapon.ts:96

## Properties

### options?

> `optional` **options**: [`WeaponOptions`](../interfaces/WeaponOptions.md)

Additional options of the weapon.

#### Defined in

item/weapon.ts:98

***

### tag

> **tag**: `string`

The weapon tag.

#### Defined in

item/weapon.ts:97

## Methods

### getAtkSkills()

> **getAtkSkills**(): [`WeaponAtkSkill`](WeaponAtkSkill.md)[]

Get this weapon's attack skill.

#### Returns

[`WeaponAtkSkill`](WeaponAtkSkill.md)[]

#### Defined in

item/weapon.ts:109

***

### getSkills()

> **getSkills**(): `undefined` \| [`WeaponSkill`](WeaponSkill.md)[]

Get this weapon`s all skills.

#### Returns

`undefined` \| [`WeaponSkill`](WeaponSkill.md)[]

#### Defined in

item/weapon.ts:103

***

### getUseSkills()

> **getUseSkills**(): [`WeaponUseSkill`](WeaponUseSkill.md)[]

Get this weapon's use skill.

#### Returns

[`WeaponUseSkill`](WeaponUseSkill.md)[]

#### Defined in

item/weapon.ts:121

***

### listeningDurability()

> **listeningDurability**(): `void`

Automatically consume durability for the tools.

#### Returns

`void`

#### Defined in

item/weapon.ts:133
