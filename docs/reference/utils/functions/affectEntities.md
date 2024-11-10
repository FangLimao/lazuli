[**@lazuli/utils v2.2.0**](../README.md) • **Docs**

***

[@lazuli/utils v2.2.0](../globals.md) / affectEntities

# Function: affectEntities()

> **affectEntities**(`dimension`, `affectOption`, `effectType`, `duration`, `effectOption`?): `void`

Affect entities within an area.

## Parameters

• **dimension**: `Dimension`

Area's dimension.

• **affectOption**: `EntityQueryOptions`

Contains options for selecting entities within an area.

• **effectType**: `string` \| `EffectType`

Type of effect to add to the entity.

• **duration**: `number`

Amount of time, in ticks, for the effect to apply.
There are 20 ticks per second. Use TicksPerSecond constant to convert between ticks and seconds.
The value must be within the range [0, 20000000].

• **effectOption?**: `EntityEffectOptions`

Additional options for the effect.

## Returns

`void`

## Defined in

entity.ts:236
