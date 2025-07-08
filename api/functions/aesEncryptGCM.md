# Function: aesEncryptGCM()

> **aesEncryptGCM**(`plaintext`, `key`, `iv`, `additionalData`): `Buffer`\<`ArrayBuffer`\>

Defined in: [src/Utils/crypto.ts:52](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/src/Utils/crypto.ts#L52)

encrypt AES 256 GCM;
where the tag tag is suffixed to the ciphertext

## Parameters

### plaintext

`Uint8Array`

### key

`Uint8Array`

### iv

`Uint8Array`

### additionalData

`Uint8Array`

## Returns

`Buffer`\<`ArrayBuffer`\>
