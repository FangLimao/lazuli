[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / WeaponTag

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

item/weapon.ts:90

## Properties

### options?

> `optional` **options**: [`WeaponOptions`](../interfaces/WeaponOptions.md)

Additional options of the weapon.

#### Defined in

item/weapon.ts:92

***

### tag

> **tag**: `string`

The weapon tag.

#### Defined in

item/weapon.ts:91

## Methods

### getAtkSkills()

> **getAtkSkills**(): [`WeaponAtkSkill`](WeaponAtkSkill.md)[]

Get this weapon's attack skill.

#### Returns

[`WeaponAtkSkill`](WeaponAtkSkill.md)[]

#### Defined in

item/weapon.ts:103

***

### getSkills()

> **getSkills**(): `undefined` \| [`WeaponSkill`](WeaponSkill.md)[]

Get this weapon`s all skills.

#### Returns

`undefined` \| [`WeaponSkill`](WeaponSkill.md)[]

#### Defined in

item/weapon.ts:97

***

### getUseSkills()

> **getUseSkills**(): [`WeaponUseSkill`](WeaponUseSkill.md)[]

Get this weapon's use skill.

#### Returns

[`WeaponUseSkill`](WeaponUseSkill.md)[]

#### Defined in

item/weapon.ts:115

***

### listeningDurability()

> **listeningDurability**(): `void`

Automatically consume durability for the tools.

#### Returns

`void`

#### Defined in

item/weapon.ts:127
