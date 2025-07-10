# Class: StickerSyncRMRMessage

Defined in: [WAProto/index.d.ts:34557](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34557)

Represents a StickerSyncRMRMessage.

## Implements

- [`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

## Constructors

### new StickerSyncRMRMessage()

> **new StickerSyncRMRMessage**(`properties`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:34563](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34563)

Constructs a new StickerSyncRMRMessage.

#### Parameters

##### properties?

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

Properties to set

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

## Properties

### filehash

> **filehash**: `string`[]

Defined in: [WAProto/index.d.ts:34566](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34566)

StickerSyncRMRMessage filehash.

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`filehash`](../interfaces/IStickerSyncRMRMessage.md#filehash)

***

### requestTimestamp?

> `optional` **requestTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:34572](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34572)

StickerSyncRMRMessage requestTimestamp.

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`requestTimestamp`](../interfaces/IStickerSyncRMRMessage.md#requesttimestamp)

***

### rmrSource?

> `optional` **rmrSource**: `null` \| `string`

Defined in: [WAProto/index.d.ts:34569](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34569)

StickerSyncRMRMessage rmrSource.

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`rmrSource`](../interfaces/IStickerSyncRMRMessage.md#rmrsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34642](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34642)

Converts this StickerSyncRMRMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:34579](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34579)

Creates a new StickerSyncRMRMessage instance using the specified properties.

#### Parameters

##### properties?

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

Properties to set

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:34605](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34605)

Decodes a StickerSyncRMRMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:34614](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34614)

Decodes a StickerSyncRMRMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34587](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34587)

Encodes the specified StickerSyncRMRMessage message. Does not implicitly [verify](StickerSyncRMRMessage.md#verify) messages.

#### Parameters

##### message

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

StickerSyncRMRMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34595](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34595)

Encodes the specified StickerSyncRMRMessage message, length delimited. Does not implicitly [verify](StickerSyncRMRMessage.md#verify) messages.

#### Parameters

##### message

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

StickerSyncRMRMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:34628](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34628)

Creates a StickerSyncRMRMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:34649](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34649)

Gets the default type url for StickerSyncRMRMessage

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

Defined in: [WAProto/index.d.ts:34636](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34636)

Creates a plain object from a StickerSyncRMRMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

StickerSyncRMRMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34621](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34621)

Verifies a StickerSyncRMRMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
