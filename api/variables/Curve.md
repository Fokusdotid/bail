# Variable: Curve

> `const` **Curve**: `object`

Defined in: [src/Utils/crypto.ts:13](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Utils/crypto.ts#L13)

## Type declaration

### generateKeyPair()

> **generateKeyPair**: () => [`KeyPair`](../type-aliases/KeyPair.md)

#### Returns

[`KeyPair`](../type-aliases/KeyPair.md)

### sharedKey()

> **sharedKey**: (`privateKey`, `publicKey`) => `Buffer`\<`any`\>

#### Parameters

##### privateKey

`Uint8Array`

##### publicKey

`Uint8Array`

#### Returns

`Buffer`\<`any`\>

### sign()

> **sign**: (`privateKey`, `buf`) => `any`

#### Parameters

##### privateKey

`Uint8Array`

##### buf

`Uint8Array`

#### Returns

`any`

### verify()

> **verify**: (`pubKey`, `message`, `signature`) => `boolean`

#### Parameters

##### pubKey

`Uint8Array`

##### message

`Uint8Array`

##### signature

`Uint8Array`

#### Returns

`boolean`
