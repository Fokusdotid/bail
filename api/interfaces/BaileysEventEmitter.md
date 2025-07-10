# Interface: BaileysEventEmitter

Defined in: [src/Types/Events.ts:112](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Events.ts#L112)

## Methods

### emit()

> **emit**\<`T`\>(`event`, `arg`): `boolean`

Defined in: [src/Types/Events.ts:116](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Events.ts#L116)

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

Defined in: [src/Types/Events.ts:114](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Events.ts#L114)

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

Defined in: [src/Types/Events.ts:113](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Events.ts#L113)

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

Defined in: [src/Types/Events.ts:115](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Events.ts#L115)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

#### Returns

`void`
