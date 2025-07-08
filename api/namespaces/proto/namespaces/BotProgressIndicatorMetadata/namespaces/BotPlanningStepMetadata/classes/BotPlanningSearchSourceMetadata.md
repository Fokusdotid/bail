# Class: BotPlanningSearchSourceMetadata

Defined in: [WAProto/index.d.ts:5807](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5807)

Represents a BotPlanningSearchSourceMetadata.

## Implements

- [`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

## Constructors

### new BotPlanningSearchSourceMetadata()

> **new BotPlanningSearchSourceMetadata**(`properties`?): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:5813](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5813)

Constructs a new BotPlanningSearchSourceMetadata.

#### Parameters

##### properties?

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

Properties to set

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

## Properties

### favIconUrl?

> `optional` **favIconUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5825](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5825)

BotPlanningSearchSourceMetadata favIconUrl.

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`favIconUrl`](../interfaces/IBotPlanningSearchSourceMetadata.md#faviconurl)

***

### provider?

> `optional` **provider**: `null` \| [`BotSearchSourceProvider`](../enumerations/BotSearchSourceProvider.md)

Defined in: [WAProto/index.d.ts:5819](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5819)

BotPlanningSearchSourceMetadata provider.

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`provider`](../interfaces/IBotPlanningSearchSourceMetadata.md#provider)

***

### sourceUrl?

> `optional` **sourceUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5822](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5822)

BotPlanningSearchSourceMetadata sourceUrl.

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`sourceUrl`](../interfaces/IBotPlanningSearchSourceMetadata.md#sourceurl)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5816](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5816)

BotPlanningSearchSourceMetadata title.

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`title`](../interfaces/IBotPlanningSearchSourceMetadata.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5895](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5895)

Converts this BotPlanningSearchSourceMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:5832](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5832)

Creates a new BotPlanningSearchSourceMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

Properties to set

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

BotPlanningSearchSourceMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:5858](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5858)

Decodes a BotPlanningSearchSourceMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

BotPlanningSearchSourceMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:5867](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5867)

Decodes a BotPlanningSearchSourceMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

BotPlanningSearchSourceMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5840](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5840)

Encodes the specified BotPlanningSearchSourceMetadata message. Does not implicitly [verify](BotPlanningSearchSourceMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

BotPlanningSearchSourceMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5848](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5848)

Encodes the specified BotPlanningSearchSourceMetadata message, length delimited. Does not implicitly [verify](BotPlanningSearchSourceMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

BotPlanningSearchSourceMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:5881](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5881)

Creates a BotPlanningSearchSourceMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

BotPlanningSearchSourceMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5902](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5902)

Gets the default type url for BotPlanningSearchSourceMetadata

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

Defined in: [WAProto/index.d.ts:5889](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5889)

Creates a plain object from a BotPlanningSearchSourceMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

BotPlanningSearchSourceMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5874](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L5874)

Verifies a BotPlanningSearchSourceMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
