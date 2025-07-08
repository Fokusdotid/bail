# Class: BCallMessage

Defined in: [WAProto/index.d.ts:19972](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L19972)

Represents a BCallMessage.

## Implements

- [`IBCallMessage`](../interfaces/IBCallMessage.md)

## Constructors

### new BCallMessage()

> **new BCallMessage**(`properties`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:19978](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L19978)

Constructs a new BCallMessage.

#### Parameters

##### properties?

[`IBCallMessage`](../interfaces/IBCallMessage.md)

Properties to set

#### Returns

[`BCallMessage`](BCallMessage.md)

## Properties

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:19990](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L19990)

BCallMessage caption.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`caption`](../interfaces/IBCallMessage.md#caption)

***

### masterKey?

> `optional` **masterKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:19987](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L19987)

BCallMessage masterKey.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`masterKey`](../interfaces/IBCallMessage.md#masterkey)

***

### mediaType?

> `optional` **mediaType**: `null` \| [`MediaType`](../namespaces/BCallMessage/enumerations/MediaType.md)

Defined in: [WAProto/index.d.ts:19984](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L19984)

BCallMessage mediaType.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`mediaType`](../interfaces/IBCallMessage.md#mediatype)

***

### sessionId?

> `optional` **sessionId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:19981](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L19981)

BCallMessage sessionId.

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`sessionId`](../interfaces/IBCallMessage.md#sessionid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20060](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20060)

Converts this BCallMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:19997](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L19997)

Creates a new BCallMessage instance using the specified properties.

#### Parameters

##### properties?

[`IBCallMessage`](../interfaces/IBCallMessage.md)

Properties to set

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:20023](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20023)

Decodes a BCallMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:20032](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20032)

Decodes a BCallMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20005](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20005)

Encodes the specified BCallMessage message. Does not implicitly [verify](BCallMessage.md#verify) messages.

#### Parameters

##### message

[`IBCallMessage`](../interfaces/IBCallMessage.md)

BCallMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20013](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20013)

Encodes the specified BCallMessage message, length delimited. Does not implicitly [verify](BCallMessage.md#verify) messages.

#### Parameters

##### message

[`IBCallMessage`](../interfaces/IBCallMessage.md)

BCallMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:20046](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20046)

Creates a BCallMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BCallMessage`](BCallMessage.md)

BCallMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:20067](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20067)

Gets the default type url for BCallMessage

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

Defined in: [WAProto/index.d.ts:20054](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20054)

Creates a plain object from a BCallMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`BCallMessage`](BCallMessage.md)

BCallMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20039](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20039)

Verifies a BCallMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
