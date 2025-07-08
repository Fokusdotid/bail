# Class: BotPlanningSearchSourcesMetadata

Defined in: [WAProto/index.d.ts:5919](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5919)

Represents a BotPlanningSearchSourcesMetadata.

## Implements

- [`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

## Constructors

### new BotPlanningSearchSourcesMetadata()

> **new BotPlanningSearchSourcesMetadata**(`properties`?): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:5925](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5925)

Constructs a new BotPlanningSearchSourcesMetadata.

#### Parameters

##### properties?

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

Properties to set

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

## Properties

### provider?

> `optional` **provider**: `null` \| [`BotPlanningSearchSourceProvider`](../namespaces/BotPlanningSearchSourcesMetadata/enumerations/BotPlanningSearchSourceProvider.md)

Defined in: [WAProto/index.d.ts:5931](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5931)

BotPlanningSearchSourcesMetadata provider.

#### Implementation of

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md).[`provider`](../interfaces/IBotPlanningSearchSourcesMetadata.md#provider)

***

### sourceTitle?

> `optional` **sourceTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5928](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5928)

BotPlanningSearchSourcesMetadata sourceTitle.

#### Implementation of

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md).[`sourceTitle`](../interfaces/IBotPlanningSearchSourcesMetadata.md#sourcetitle)

***

### sourceUrl?

> `optional` **sourceUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5934](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5934)

BotPlanningSearchSourcesMetadata sourceUrl.

#### Implementation of

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md).[`sourceUrl`](../interfaces/IBotPlanningSearchSourcesMetadata.md#sourceurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6004](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L6004)

Converts this BotPlanningSearchSourcesMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:5941](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5941)

Creates a new BotPlanningSearchSourcesMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

Properties to set

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

BotPlanningSearchSourcesMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:5967](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5967)

Decodes a BotPlanningSearchSourcesMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

BotPlanningSearchSourcesMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:5976](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5976)

Decodes a BotPlanningSearchSourcesMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

BotPlanningSearchSourcesMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5949](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5949)

Encodes the specified BotPlanningSearchSourcesMetadata message. Does not implicitly [verify](BotPlanningSearchSourcesMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

BotPlanningSearchSourcesMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5957](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5957)

Encodes the specified BotPlanningSearchSourcesMetadata message, length delimited. Does not implicitly [verify](BotPlanningSearchSourcesMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

BotPlanningSearchSourcesMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:5990](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5990)

Creates a BotPlanningSearchSourcesMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

BotPlanningSearchSourcesMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6011](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L6011)

Gets the default type url for BotPlanningSearchSourcesMetadata

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

Defined in: [WAProto/index.d.ts:5998](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5998)

Creates a plain object from a BotPlanningSearchSourcesMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

BotPlanningSearchSourcesMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5983](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L5983)

Verifies a BotPlanningSearchSourcesMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
