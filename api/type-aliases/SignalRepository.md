# Type Alias: SignalRepository

> **SignalRepository**: `object`

Defined in: [src/Types/Signal.ts:52](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/Signal.ts#L52)

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
