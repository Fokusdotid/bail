# Class: FullHistorySyncOnDemandRequest

Defined in: [WAProto/index.d.ts:29391](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29391)

Represents a FullHistorySyncOnDemandRequest.

## Implements

- [`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

## Constructors

### new FullHistorySyncOnDemandRequest()

> **new FullHistorySyncOnDemandRequest**(`properties`?): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29397](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29397)

Constructs a new FullHistorySyncOnDemandRequest.

#### Parameters

##### properties?

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

Properties to set

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

## Properties

### historySyncConfig?

> `optional` **historySyncConfig**: `null` \| [`IHistorySyncConfig`](../../../../DeviceProps/interfaces/IHistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:29403](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29403)

FullHistorySyncOnDemandRequest historySyncConfig.

#### Implementation of

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md).[`historySyncConfig`](../interfaces/IFullHistorySyncOnDemandRequest.md#historysyncconfig)

***

### requestMetadata?

> `optional` **requestMetadata**: `null` \| [`IFullHistorySyncOnDemandRequestMetadata`](../../../interfaces/IFullHistorySyncOnDemandRequestMetadata.md)

Defined in: [WAProto/index.d.ts:29400](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29400)

FullHistorySyncOnDemandRequest requestMetadata.

#### Implementation of

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md).[`requestMetadata`](../interfaces/IFullHistorySyncOnDemandRequest.md#requestmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29473](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29473)

Converts this FullHistorySyncOnDemandRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29410](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29410)

Creates a new FullHistorySyncOnDemandRequest instance using the specified properties.

#### Parameters

##### properties?

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

Properties to set

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

FullHistorySyncOnDemandRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29436](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29436)

Decodes a FullHistorySyncOnDemandRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

FullHistorySyncOnDemandRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29445](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29445)

Decodes a FullHistorySyncOnDemandRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

FullHistorySyncOnDemandRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29418](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29418)

Encodes the specified FullHistorySyncOnDemandRequest message. Does not implicitly [verify](FullHistorySyncOnDemandRequest.md#verify) messages.

#### Parameters

##### message

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

FullHistorySyncOnDemandRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29426](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29426)

Encodes the specified FullHistorySyncOnDemandRequest message, length delimited. Does not implicitly [verify](FullHistorySyncOnDemandRequest.md#verify) messages.

#### Parameters

##### message

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

FullHistorySyncOnDemandRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29459](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29459)

Creates a FullHistorySyncOnDemandRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

FullHistorySyncOnDemandRequest

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:29480](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29480)

Gets the default type url for FullHistorySyncOnDemandRequest

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

Defined in: [WAProto/index.d.ts:29467](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29467)

Creates a plain object from a FullHistorySyncOnDemandRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

FullHistorySyncOnDemandRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29452](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29452)

Verifies a FullHistorySyncOnDemandRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
