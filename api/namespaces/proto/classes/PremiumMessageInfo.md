# Class: PremiumMessageInfo

Defined in: [WAProto/index.d.ts:39839](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39839)

Represents a PremiumMessageInfo.

## Implements

- [`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

## Constructors

### new PremiumMessageInfo()

> **new PremiumMessageInfo**(`properties`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:39845](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39845)

Constructs a new PremiumMessageInfo.

#### Parameters

##### properties?

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

Properties to set

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

## Properties

### serverCampaignId?

> `optional` **serverCampaignId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:39848](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39848)

PremiumMessageInfo serverCampaignId.

#### Implementation of

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md).[`serverCampaignId`](../interfaces/IPremiumMessageInfo.md#servercampaignid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:39918](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39918)

Converts this PremiumMessageInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:39855](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39855)

Creates a new PremiumMessageInfo instance using the specified properties.

#### Parameters

##### properties?

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

Properties to set

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:39881](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39881)

Decodes a PremiumMessageInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:39890](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39890)

Decodes a PremiumMessageInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39863](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39863)

Encodes the specified PremiumMessageInfo message. Does not implicitly [verify](PremiumMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

PremiumMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39871](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39871)

Encodes the specified PremiumMessageInfo message, length delimited. Does not implicitly [verify](PremiumMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

PremiumMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:39904](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39904)

Creates a PremiumMessageInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:39925](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39925)

Gets the default type url for PremiumMessageInfo

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

Defined in: [WAProto/index.d.ts:39912](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39912)

Creates a plain object from a PremiumMessageInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`PremiumMessageInfo`](PremiumMessageInfo.md)

PremiumMessageInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:39897](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39897)

Verifies a PremiumMessageInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
