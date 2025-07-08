# Class: PreKeySignalMessage

Defined in: [WAProto/index.d.ts:39727](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39727)

Represents a PreKeySignalMessage.

## Implements

- [`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

## Constructors

### new PreKeySignalMessage()

> **new PreKeySignalMessage**(`properties`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:39733](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39733)

Constructs a new PreKeySignalMessage.

#### Parameters

##### properties?

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

Properties to set

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

## Properties

### baseKey?

> `optional` **baseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:39745](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39745)

PreKeySignalMessage baseKey.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`baseKey`](../interfaces/IPreKeySignalMessage.md#basekey)

***

### identityKey?

> `optional` **identityKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:39748](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39748)

PreKeySignalMessage identityKey.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`identityKey`](../interfaces/IPreKeySignalMessage.md#identitykey)

***

### message?

> `optional` **message**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:39751](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39751)

PreKeySignalMessage message.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`message`](../interfaces/IPreKeySignalMessage.md#message)

***

### preKeyId?

> `optional` **preKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:39739](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39739)

PreKeySignalMessage preKeyId.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`preKeyId`](../interfaces/IPreKeySignalMessage.md#prekeyid)

***

### registrationId?

> `optional` **registrationId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:39736](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39736)

PreKeySignalMessage registrationId.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`registrationId`](../interfaces/IPreKeySignalMessage.md#registrationid)

***

### signedPreKeyId?

> `optional` **signedPreKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:39742](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39742)

PreKeySignalMessage signedPreKeyId.

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`signedPreKeyId`](../interfaces/IPreKeySignalMessage.md#signedprekeyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:39821](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39821)

Converts this PreKeySignalMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:39758](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39758)

Creates a new PreKeySignalMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

Properties to set

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:39784](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39784)

Decodes a PreKeySignalMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:39793](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39793)

Decodes a PreKeySignalMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39766](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39766)

Encodes the specified PreKeySignalMessage message. Does not implicitly [verify](PreKeySignalMessage.md#verify) messages.

#### Parameters

##### message

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

PreKeySignalMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39774](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39774)

Encodes the specified PreKeySignalMessage message, length delimited. Does not implicitly [verify](PreKeySignalMessage.md#verify) messages.

#### Parameters

##### message

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

PreKeySignalMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:39807](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39807)

Creates a PreKeySignalMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:39828](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39828)

Gets the default type url for PreKeySignalMessage

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

Defined in: [WAProto/index.d.ts:39815](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39815)

Creates a plain object from a PreKeySignalMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PreKeySignalMessage`](PreKeySignalMessage.md)

PreKeySignalMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:39800](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L39800)

Verifies a PreKeySignalMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
