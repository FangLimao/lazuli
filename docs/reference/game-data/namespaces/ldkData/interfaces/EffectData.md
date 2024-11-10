[**@lazuli/game-data v2.2.0**](../../../README.md) • **Docs**

***

[@lazuli/game-data v2.2.0](../../../globals.md) / [ldkData](../README.md) / EffectData

# Interface: EffectData

Effect data.

## Properties

### amplifier?

> `optional` **amplifier**: `number`

The strength of the effect.

#### Defined in

ldk.ts:48

***

### duration

> **duration**: `number`

Amount of time, in ticks, for the effect to apply.
There are 20 ticks per second. Use TicksPerSecond constant to convert between ticks and seconds.
The value must be within he range [0, 20000000].

#### Defined in

ldk.ts:44

***

### effectType

> **effectType**: `string` \| `EffectType`

Type of effect to add to the entity.

#### Defined in

ldk.ts:38

***

### showParticles?

> `optional` **showParticles**: `boolean`

If true, will show particles when effect is on the entity.

#### Defined in

ldk.ts:52
