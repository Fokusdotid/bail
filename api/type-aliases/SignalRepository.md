# Type Alias: SignalRepository

> **SignalRepository**: `object`

Defined in: [src/Types/Signal.ts:52](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Signal.ts#L52)

## Type declaration

### decryptGroupMessage()

#### Parameters

##### opts

`DecryptGroupSignalOpts`

#### Returns

`Promise`\<`Uint8Array`\<`ArrayBufferLike`\>\>

### decryptMessage()

#### Parameters

##### opts

`DecryptSignalProtoOpts`

#### Returns

`Promise`\<`Uint8Array`\<`ArrayBufferLike`\>\>

### encryptGroupMessage()

#### Parameters

##### opts

`EncryptGroupMessageOpts`

#### Returns

`Promise`\<\{ `ciphertext`: `Uint8Array`; `senderKeyDistributionMessage`: `Uint8Array`; \}\>

### encryptMessage()

#### Parameters

##### opts

`EncryptMessageOpts`

#### Returns

`Promise`\<\{ `ciphertext`: `Uint8Array`; `type`: `"pkmsg"` \| `"msg"`; \}\>

### injectE2ESession()

#### Parameters

##### opts

`E2ESessionOpts`

#### Returns

`Promise`\<`void`\>

### jidToSignalProtocolAddress()

#### Parameters

##### jid

`string`

#### Returns

`string`

### processSenderKeyDistributionMessage()

#### Parameters

##### opts

`ProcessSenderKeyDistributionMessageOpts`

#### Returns

`Promise`\<`void`\>
