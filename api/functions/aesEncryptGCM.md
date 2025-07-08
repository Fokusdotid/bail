# Function: aesEncryptGCM()

> **aesEncryptGCM**(`plaintext`, `key`, `iv`, `additionalData`): `Buffer`\<`ArrayBuffer`\>

Defined in: [src/Utils/crypto.ts:52](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/src/Utils/crypto.ts#L52)

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
