# Function: aesDecryptGCM()

> **aesDecryptGCM**(`ciphertext`, `key`, `iv`, `additionalData`): `Buffer`\<`ArrayBuffer`\>

Defined in: [src/Utils/crypto.ts:62](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/src/Utils/crypto.ts#L62)

decrypt AES 256 GCM;
where the auth tag is suffixed to the ciphertext

## Parameters

### ciphertext

`Uint8Array`

### key

`Uint8Array`

### iv

`Uint8Array`

### additionalData

`Uint8Array`

## Returns

`Buffer`\<`ArrayBuffer`\>
