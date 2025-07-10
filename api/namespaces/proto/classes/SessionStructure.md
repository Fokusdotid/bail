# Class: SessionStructure

Defined in: [WAProto/index.d.ts:41822](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41822)

Represents a SessionStructure.

## Implements

- [`ISessionStructure`](../interfaces/ISessionStructure.md)

## Constructors

### new SessionStructure()

> **new SessionStructure**(`properties`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:41828](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41828)

Constructs a new SessionStructure.

#### Parameters

##### properties?

[`ISessionStructure`](../interfaces/ISessionStructure.md)

Properties to set

#### Returns

[`SessionStructure`](SessionStructure.md)

## Properties

### aliceBaseKey?

> `optional` **aliceBaseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41867](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41867)

SessionStructure aliceBaseKey.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`aliceBaseKey`](../interfaces/ISessionStructure.md#alicebasekey)

***

### localIdentityPublic?

> `optional` **localIdentityPublic**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41834](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41834)

SessionStructure localIdentityPublic.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`localIdentityPublic`](../interfaces/ISessionStructure.md#localidentitypublic)

***

### localRegistrationId?

> `optional` **localRegistrationId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:41861](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41861)

SessionStructure localRegistrationId.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`localRegistrationId`](../interfaces/ISessionStructure.md#localregistrationid)

***

### needsRefresh?

> `optional` **needsRefresh**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:41864](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41864)

SessionStructure needsRefresh.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`needsRefresh`](../interfaces/ISessionStructure.md#needsrefresh)

***

### pendingKeyExchange?

> `optional` **pendingKeyExchange**: `null` \| [`IPendingKeyExchange`](../namespaces/SessionStructure/interfaces/IPendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:41852](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41852)

SessionStructure pendingKeyExchange.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`pendingKeyExchange`](../interfaces/ISessionStructure.md#pendingkeyexchange)

***

### pendingPreKey?

> `optional` **pendingPreKey**: `null` \| [`IPendingPreKey`](../namespaces/SessionStructure/interfaces/IPendingPreKey.md)

Defined in: [WAProto/index.d.ts:41855](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41855)

SessionStructure pendingPreKey.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`pendingPreKey`](../interfaces/ISessionStructure.md#pendingprekey)

***

### previousCounter?

> `optional` **previousCounter**: `null` \| `number`

Defined in: [WAProto/index.d.ts:41843](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41843)

SessionStructure previousCounter.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`previousCounter`](../interfaces/ISessionStructure.md#previouscounter)

***

### receiverChains

> **receiverChains**: [`IChain`](../namespaces/SessionStructure/interfaces/IChain.md)[]

Defined in: [WAProto/index.d.ts:41849](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41849)

SessionStructure receiverChains.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`receiverChains`](../interfaces/ISessionStructure.md#receiverchains)

***

### remoteIdentityPublic?

> `optional` **remoteIdentityPublic**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41837](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41837)

SessionStructure remoteIdentityPublic.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`remoteIdentityPublic`](../interfaces/ISessionStructure.md#remoteidentitypublic)

***

### remoteRegistrationId?

> `optional` **remoteRegistrationId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:41858](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41858)

SessionStructure remoteRegistrationId.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`remoteRegistrationId`](../interfaces/ISessionStructure.md#remoteregistrationid)

***

### rootKey?

> `optional` **rootKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41840](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41840)

SessionStructure rootKey.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`rootKey`](../interfaces/ISessionStructure.md#rootkey)

***

### senderChain?

> `optional` **senderChain**: `null` \| [`IChain`](../namespaces/SessionStructure/interfaces/IChain.md)

Defined in: [WAProto/index.d.ts:41846](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41846)

SessionStructure senderChain.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`senderChain`](../interfaces/ISessionStructure.md#senderchain)

***

### sessionVersion?

> `optional` **sessionVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:41831](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41831)

SessionStructure sessionVersion.

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`sessionVersion`](../interfaces/ISessionStructure.md#sessionversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:41937](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41937)

Converts this SessionStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:41874](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41874)

Creates a new SessionStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISessionStructure`](../interfaces/ISessionStructure.md)

Properties to set

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:41900](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41900)

Decodes a SessionStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:41909](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41909)

Decodes a SessionStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41882](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41882)

Encodes the specified SessionStructure message. Does not implicitly [verify](SessionStructure.md#verify) messages.

#### Parameters

##### message

[`ISessionStructure`](../interfaces/ISessionStructure.md)

SessionStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41890](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41890)

Encodes the specified SessionStructure message, length delimited. Does not implicitly [verify](SessionStructure.md#verify) messages.

#### Parameters

##### message

[`ISessionStructure`](../interfaces/ISessionStructure.md)

SessionStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:41923](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41923)

Creates a SessionStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SessionStructure`](SessionStructure.md)

SessionStructure

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:41944](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41944)

Gets the default type url for SessionStructure

#### Parameters

##### typeUrlPrefix?

`string`

your custom typeUrlPrefix(default "type.googleapis.com")

#### Returns

`string`

The default type url

***

### toObject()

> `static` **toObject**(`message`, `options`?): `object`

Defined in: [WAProto/index.d.ts:41931](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41931)

Creates a plain object from a SessionStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SessionStructure`](SessionStructure.md)

SessionStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:41916](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41916)

Verifies a SessionStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
