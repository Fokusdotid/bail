# Class: SenderChainKey

Defined in: [WAProto/index.d.ts:41382](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41382)

Represents a SenderChainKey.

## Implements

- [`ISenderChainKey`](../interfaces/ISenderChainKey.md)

## Constructors

### new SenderChainKey()

> **new SenderChainKey**(`properties`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:41388](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41388)

Constructs a new SenderChainKey.

#### Parameters

##### properties?

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

Properties to set

#### Returns

[`SenderChainKey`](SenderChainKey.md)

## Properties

### iteration?

> `optional` **iteration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:41391](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41391)

SenderChainKey iteration.

#### Implementation of

[`ISenderChainKey`](../interfaces/ISenderChainKey.md).[`iteration`](../interfaces/ISenderChainKey.md#iteration)

***

### seed?

> `optional` **seed**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41394](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41394)

SenderChainKey seed.

#### Implementation of

[`ISenderChainKey`](../interfaces/ISenderChainKey.md).[`seed`](../interfaces/ISenderChainKey.md#seed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:41464](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41464)

Converts this SenderChainKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:41401](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41401)

Creates a new SenderChainKey instance using the specified properties.

#### Parameters

##### properties?

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

Properties to set

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:41427](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41427)

Decodes a SenderChainKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:41436](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41436)

Decodes a SenderChainKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41409](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41409)

Encodes the specified SenderChainKey message. Does not implicitly [verify](SenderChainKey.md#verify) messages.

#### Parameters

##### message

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

SenderChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41417](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41417)

Encodes the specified SenderChainKey message, length delimited. Does not implicitly [verify](SenderChainKey.md#verify) messages.

#### Parameters

##### message

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

SenderChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:41450](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41450)

Creates a SenderChainKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:41471](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41471)

Gets the default type url for SenderChainKey

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

Defined in: [WAProto/index.d.ts:41458](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41458)

Creates a plain object from a SenderChainKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderChainKey`](SenderChainKey.md)

SenderChainKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:41443](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L41443)

Verifies a SenderChainKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
