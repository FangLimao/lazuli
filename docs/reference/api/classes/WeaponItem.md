[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / WeaponItem

# Class: WeaponItem

Define a tool.

## Constructors

### new WeaponItem()

> **new WeaponItem**(`item`, `options`?): [`WeaponItem`](WeaponItem.md)

#### Parameters

• **item**: `ItemStack`

Item of the weapon.

• **options?**: [`WeaponOptions`](../interfaces/WeaponOptions.md)

Additional options of the weapon.

#### Returns

[`WeaponItem`](WeaponItem.md)

#### Defined in

item/weapon.ts:162

## Properties

### item

> **item**: `ItemStack`

Item of the weapon.

#### Defined in

item/weapon.ts:163

***

### options?

> `optional` **options**: [`WeaponOptions`](../interfaces/WeaponOptions.md)

Additional options of the weapon.

#### Defined in

item/weapon.ts:164

## Methods

### getAtkSkills()

> **getAtkSkills**(): [`WeaponAtkSkill`](WeaponAtkSkill.md)[]

Get this weapon's attack skill.

#### Returns

[`WeaponAtkSkill`](WeaponAtkSkill.md)[]

#### Defined in

item/weapon.ts:175

***

### getSkills()

> **getSkills**(): `undefined` \| [`WeaponSkill`](WeaponSkill.md)[]

Get this weapon`s all skills.

#### Returns

`undefined` \| [`WeaponSkill`](WeaponSkill.md)[]

#### Defined in

item/weapon.ts:169

***

### getUseSkills()

> **getUseSkills**(): [`WeaponUseSkill`](WeaponUseSkill.md)[]

Get this weapon's use skill.

#### Returns

[`WeaponUseSkill`](WeaponUseSkill.md)[]

#### Defined in

item/weapon.ts:187

***

### listeningDurability()

> **listeningDurability**(): `void`

Automatically consume durability for the tools.

#### Returns

`void`

#### Defined in

item/weapon.ts:199
