# Class: MediaRetryNotification

Defined in: [WAProto/index.d.ts:18116](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18116)

Represents a MediaRetryNotification.

## Implements

- [`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

## Constructors

### new MediaRetryNotification()

> **new MediaRetryNotification**(`properties`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:18122](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18122)

Constructs a new MediaRetryNotification.

#### Parameters

##### properties?

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

Properties to set

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

## Properties

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:18128](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18128)

MediaRetryNotification directPath.

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`directPath`](../interfaces/IMediaRetryNotification.md#directpath)

***

### messageSecret?

> `optional` **messageSecret**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:18134](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18134)

MediaRetryNotification messageSecret.

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`messageSecret`](../interfaces/IMediaRetryNotification.md#messagesecret)

***

### result?

> `optional` **result**: `null` \| [`ResultType`](../namespaces/MediaRetryNotification/enumerations/ResultType.md)

Defined in: [WAProto/index.d.ts:18131](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18131)

MediaRetryNotification result.

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`result`](../interfaces/IMediaRetryNotification.md#result)

***

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:18125](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18125)

MediaRetryNotification stanzaId.

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`stanzaId`](../interfaces/IMediaRetryNotification.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:18204](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18204)

Converts this MediaRetryNotification to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:18141](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18141)

Creates a new MediaRetryNotification instance using the specified properties.

#### Parameters

##### properties?

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

Properties to set

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:18167](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18167)

Decodes a MediaRetryNotification message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:18176](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18176)

Decodes a MediaRetryNotification message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18149](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18149)

Encodes the specified MediaRetryNotification message. Does not implicitly [verify](MediaRetryNotification.md#verify) messages.

#### Parameters

##### message

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

MediaRetryNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18157](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18157)

Encodes the specified MediaRetryNotification message, length delimited. Does not implicitly [verify](MediaRetryNotification.md#verify) messages.

#### Parameters

##### message

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

MediaRetryNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:18190](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18190)

Creates a MediaRetryNotification message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:18211](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18211)

Gets the default type url for MediaRetryNotification

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

Defined in: [WAProto/index.d.ts:18198](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18198)

Creates a plain object from a MediaRetryNotification message. Also converts values to other types if specified.

#### Parameters

##### message

[`MediaRetryNotification`](MediaRetryNotification.md)

MediaRetryNotification

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:18183](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L18183)

Verifies a MediaRetryNotification message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
