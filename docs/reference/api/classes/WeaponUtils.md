[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / WeaponUtils

# Class: WeaponUtils

Some useful functions for Weapon Api.

## Constructors

### new WeaponUtils()

> **new WeaponUtils**(): [`WeaponUtils`](WeaponUtils.md)

#### Returns

[`WeaponUtils`](WeaponUtils.md)

## Methods

### onDurabilityDisposeTrigger()

> `static` **onDurabilityDisposeTrigger**(`holder`, `item`, `weapon`): `void`

#### Parameters

• **holder**: `Entity`

• **item**: `ItemStack`

• **weapon**: [`WeaponItem`](WeaponItem.md) \| [`WeaponTag`](WeaponTag.md)

#### Returns

`void`

#### Defined in

item/weapon.ts:53

***

### onHitTrigger()

> `static` **onHitTrigger**(`weapon`, `hitter`, `target`): `void`

#### Parameters

• **weapon**: [`WeaponItem`](WeaponItem.md) \| [`WeaponTag`](WeaponTag.md)

• **hitter**: `Entity`

• **target**: `Entity`

#### Returns

`void`

#### Defined in

item/weapon.ts:32

***

### onUseTrigger()

> `static` **onUseTrigger**(`weapon`, `player`): `void`

#### Parameters

• **weapon**: [`WeaponItem`](WeaponItem.md) \| [`WeaponTag`](WeaponTag.md)

• **player**: `Player`

#### Returns

`void`

#### Defined in

item/weapon.ts:15
