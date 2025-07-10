# Class: PollOption

Defined in: [WAProto/index.d.ts:36937](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36937)

Represents a PollOption.

## Implements

- [`IPollOption`](../interfaces/IPollOption.md)

## Constructors

### new PollOption()

> **new PollOption**(`properties`?): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:36943](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36943)

Constructs a new PollOption.

#### Parameters

##### properties?

[`IPollOption`](../interfaces/IPollOption.md)

Properties to set

#### Returns

[`PollOption`](PollOption.md)

## Properties

### hash?

> `optional` **hash**: `null` \| `string`

Defined in: [WAProto/index.d.ts:36949](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36949)

PollOption hash.

#### Implementation of

[`IPollOption`](../interfaces/IPollOption.md).[`hash`](../interfaces/IPollOption.md#hash)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:36946](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36946)

PollOption name.

#### Implementation of

[`IPollOption`](../interfaces/IPollOption.md).[`name`](../interfaces/IPollOption.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37019](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37019)

Converts this PollOption to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:36956](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36956)

Creates a new PollOption instance using the specified properties.

#### Parameters

##### properties?

[`IPollOption`](../interfaces/IPollOption.md)

Properties to set

#### Returns

[`PollOption`](PollOption.md)

PollOption instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:36982](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36982)

Decodes a PollOption message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollOption`](PollOption.md)

PollOption

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:36991](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36991)

Decodes a PollOption message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollOption`](PollOption.md)

PollOption

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36964](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36964)

Encodes the specified PollOption message. Does not implicitly [verify](PollOption.md#verify) messages.

#### Parameters

##### message

[`IPollOption`](../interfaces/IPollOption.md)

PollOption message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36972](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36972)

Encodes the specified PollOption message, length delimited. Does not implicitly [verify](PollOption.md#verify) messages.

#### Parameters

##### message

[`IPollOption`](../interfaces/IPollOption.md)

PollOption message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:37005](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37005)

Creates a PollOption message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollOption`](PollOption.md)

PollOption

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:37026](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37026)

Gets the default type url for PollOption

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

Defined in: [WAProto/index.d.ts:37013](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37013)

Creates a plain object from a PollOption message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollOption`](PollOption.md)

PollOption

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:36998](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L36998)

Verifies a PollOption message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
