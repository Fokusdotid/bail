# Class: PollVoteMessage

Defined in: [WAProto/index.d.ts:32075](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32075)

Represents a PollVoteMessage.

## Implements

- [`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

## Constructors

### new PollVoteMessage()

> **new PollVoteMessage**(`properties`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:32081](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32081)

Constructs a new PollVoteMessage.

#### Parameters

##### properties?

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

Properties to set

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

## Properties

### selectedOptions

> **selectedOptions**: `Uint8Array`\<`ArrayBufferLike`\>[]

Defined in: [WAProto/index.d.ts:32084](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32084)

PollVoteMessage selectedOptions.

#### Implementation of

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md).[`selectedOptions`](../interfaces/IPollVoteMessage.md#selectedoptions)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32154](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32154)

Converts this PollVoteMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:32091](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32091)

Creates a new PollVoteMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

Properties to set

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:32117](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32117)

Decodes a PollVoteMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:32126](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32126)

Decodes a PollVoteMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32099](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32099)

Encodes the specified PollVoteMessage message. Does not implicitly [verify](PollVoteMessage.md#verify) messages.

#### Parameters

##### message

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

PollVoteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32107](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32107)

Encodes the specified PollVoteMessage message, length delimited. Does not implicitly [verify](PollVoteMessage.md#verify) messages.

#### Parameters

##### message

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

PollVoteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:32140](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32140)

Creates a PollVoteMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:32161](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32161)

Gets the default type url for PollVoteMessage

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

Defined in: [WAProto/index.d.ts:32148](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32148)

Creates a plain object from a PollVoteMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollVoteMessage`](PollVoteMessage.md)

PollVoteMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32133](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L32133)

Verifies a PollVoteMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
