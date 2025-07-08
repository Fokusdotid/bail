# Function: bindWaitForEvent()

> **bindWaitForEvent**\<`T`\>(`ev`, `event`): (`check`, `timeoutMs`?) => `Promise`\<`void`\>

Defined in: [src/Utils/generics.ts:212](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Utils/generics.ts#L212)

## Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

## Parameters

### ev

[`BaileysEventEmitter`](../interfaces/BaileysEventEmitter.md)

### event

`T`

## Returns

`Function`

### Parameters

#### check

(`u`) => `Promise`\<`undefined` \| `boolean`\>

#### timeoutMs?

`number`

### Returns

`Promise`\<`void`\>
