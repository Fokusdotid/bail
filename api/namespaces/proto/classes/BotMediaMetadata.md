# Class: BotMediaMetadata

Defined in: [WAProto/index.d.ts:4337](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4337)

Represents a BotMediaMetadata.

## Implements

- [`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

## Constructors

### new BotMediaMetadata()

> **new BotMediaMetadata**(`properties`?): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:4343](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4343)

Constructs a new BotMediaMetadata.

#### Parameters

##### properties?

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

Properties to set

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

## Properties

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4355](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4355)

BotMediaMetadata directPath.

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`directPath`](../interfaces/IBotMediaMetadata.md#directpath)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4352](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4352)

BotMediaMetadata fileEncSha256.

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`fileEncSha256`](../interfaces/IBotMediaMetadata.md#fileencsha256)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4346](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4346)

BotMediaMetadata fileSha256.

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`fileSha256`](../interfaces/IBotMediaMetadata.md#filesha256)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4349](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4349)

BotMediaMetadata mediaKey.

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`mediaKey`](../interfaces/IBotMediaMetadata.md#mediakey)

***

### mediaKeyTimestamp?

> `optional` **mediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4358](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4358)

BotMediaMetadata mediaKeyTimestamp.

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`mediaKeyTimestamp`](../interfaces/IBotMediaMetadata.md#mediakeytimestamp)

***

### mimetype?

> `optional` **mimetype**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4361](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4361)

BotMediaMetadata mimetype.

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`mimetype`](../interfaces/IBotMediaMetadata.md#mimetype)

***

### orientationType?

> `optional` **orientationType**: `null` \| [`OrientationType`](../namespaces/BotMediaMetadata/enumerations/OrientationType.md)

Defined in: [WAProto/index.d.ts:4364](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4364)

BotMediaMetadata orientationType.

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`orientationType`](../interfaces/IBotMediaMetadata.md#orientationtype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4434](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4434)

Converts this BotMediaMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:4371](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4371)

Creates a new BotMediaMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

Properties to set

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

BotMediaMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:4397](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4397)

Decodes a BotMediaMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

BotMediaMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:4406](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4406)

Decodes a BotMediaMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

BotMediaMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4379](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4379)

Encodes the specified BotMediaMetadata message. Does not implicitly [verify](BotMediaMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

BotMediaMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4387](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4387)

Encodes the specified BotMediaMetadata message, length delimited. Does not implicitly [verify](BotMediaMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

BotMediaMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:4420](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4420)

Creates a BotMediaMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

BotMediaMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4441](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4441)

Gets the default type url for BotMediaMetadata

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

Defined in: [WAProto/index.d.ts:4428](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4428)

Creates a plain object from a BotMediaMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotMediaMetadata`](BotMediaMetadata.md)

BotMediaMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4413](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L4413)

Verifies a BotMediaMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
