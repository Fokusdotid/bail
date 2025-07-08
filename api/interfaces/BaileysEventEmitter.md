# Interface: BaileysEventEmitter

Defined in: [src/Types/Events.ts:112](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Events.ts#L112)

## Methods

### emit()

> **emit**\<`T`\>(`event`, `arg`): `boolean`

Defined in: [src/Types/Events.ts:116](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Events.ts#L116)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

##### arg

[`BaileysEventMap`](../type-aliases/BaileysEventMap.md)\[`T`\]

#### Returns

`boolean`

***

### off()

> **off**\<`T`\>(`event`, `listener`): `void`

Defined in: [src/Types/Events.ts:114](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Events.ts#L114)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

##### listener

(`arg`) => `void`

#### Returns

`void`

***

### on()

> **on**\<`T`\>(`event`, `listener`): `void`

Defined in: [src/Types/Events.ts:113](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Events.ts#L113)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

##### listener

(`arg`) => `void`

#### Returns

`void`

***

### removeAllListeners()

> **removeAllListeners**\<`T`\>(`event`): `void`

Defined in: [src/Types/Events.ts:115](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Events.ts#L115)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

#### Returns

`void`
