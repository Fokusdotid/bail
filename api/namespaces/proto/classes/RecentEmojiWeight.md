# Class: RecentEmojiWeight

Defined in: [WAProto/index.d.ts:40526](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40526)

Represents a RecentEmojiWeight.

## Implements

- [`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

## Constructors

### new RecentEmojiWeight()

> **new RecentEmojiWeight**(`properties`?): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:40532](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40532)

Constructs a new RecentEmojiWeight.

#### Parameters

##### properties?

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

Properties to set

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

## Properties

### emoji?

> `optional` **emoji**: `null` \| `string`

Defined in: [WAProto/index.d.ts:40535](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40535)

RecentEmojiWeight emoji.

#### Implementation of

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md).[`emoji`](../interfaces/IRecentEmojiWeight.md#emoji)

***

### weight?

> `optional` **weight**: `null` \| `number`

Defined in: [WAProto/index.d.ts:40538](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40538)

RecentEmojiWeight weight.

#### Implementation of

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md).[`weight`](../interfaces/IRecentEmojiWeight.md#weight)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:40608](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40608)

Converts this RecentEmojiWeight to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:40545](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40545)

Creates a new RecentEmojiWeight instance using the specified properties.

#### Parameters

##### properties?

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

Properties to set

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

RecentEmojiWeight instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:40571](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40571)

Decodes a RecentEmojiWeight message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

RecentEmojiWeight

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:40580](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40580)

Decodes a RecentEmojiWeight message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

RecentEmojiWeight

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40553](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40553)

Encodes the specified RecentEmojiWeight message. Does not implicitly [verify](RecentEmojiWeight.md#verify) messages.

#### Parameters

##### message

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

RecentEmojiWeight message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40561](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40561)

Encodes the specified RecentEmojiWeight message, length delimited. Does not implicitly [verify](RecentEmojiWeight.md#verify) messages.

#### Parameters

##### message

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

RecentEmojiWeight message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:40594](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40594)

Creates a RecentEmojiWeight message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

RecentEmojiWeight

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:40615](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40615)

Gets the default type url for RecentEmojiWeight

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

Defined in: [WAProto/index.d.ts:40602](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40602)

Creates a plain object from a RecentEmojiWeight message. Also converts values to other types if specified.

#### Parameters

##### message

[`RecentEmojiWeight`](RecentEmojiWeight.md)

RecentEmojiWeight

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:40587](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L40587)

Verifies a RecentEmojiWeight message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
