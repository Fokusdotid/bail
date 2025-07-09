# Class: BotPlanningStepSectionMetadata

Defined in: [WAProto/index.d.ts:6039](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6039)

Represents a BotPlanningStepSectionMetadata.

## Implements

- [`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

## Constructors

### new BotPlanningStepSectionMetadata()

> **new BotPlanningStepSectionMetadata**(`properties`?): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:6045](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6045)

Constructs a new BotPlanningStepSectionMetadata.

#### Parameters

##### properties?

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

Properties to set

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

## Properties

### sectionBody?

> `optional` **sectionBody**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6051](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6051)

BotPlanningStepSectionMetadata sectionBody.

#### Implementation of

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md).[`sectionBody`](../interfaces/IBotPlanningStepSectionMetadata.md#sectionbody)

***

### sectionTitle?

> `optional` **sectionTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6048](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6048)

BotPlanningStepSectionMetadata sectionTitle.

#### Implementation of

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md).[`sectionTitle`](../interfaces/IBotPlanningStepSectionMetadata.md#sectiontitle)

***

### sourcesMetadata

> **sourcesMetadata**: [`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)[]

Defined in: [WAProto/index.d.ts:6054](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6054)

BotPlanningStepSectionMetadata sourcesMetadata.

#### Implementation of

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md).[`sourcesMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md#sourcesmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6124](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6124)

Converts this BotPlanningStepSectionMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:6061](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6061)

Creates a new BotPlanningStepSectionMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

Properties to set

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

BotPlanningStepSectionMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:6087](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6087)

Decodes a BotPlanningStepSectionMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

BotPlanningStepSectionMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:6096](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6096)

Decodes a BotPlanningStepSectionMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

BotPlanningStepSectionMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6069](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6069)

Encodes the specified BotPlanningStepSectionMetadata message. Does not implicitly [verify](BotPlanningStepSectionMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

BotPlanningStepSectionMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6077](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6077)

Encodes the specified BotPlanningStepSectionMetadata message, length delimited. Does not implicitly [verify](BotPlanningStepSectionMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

BotPlanningStepSectionMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:6110](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6110)

Creates a BotPlanningStepSectionMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

BotPlanningStepSectionMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6131](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6131)

Gets the default type url for BotPlanningStepSectionMetadata

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

Defined in: [WAProto/index.d.ts:6118](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6118)

Creates a plain object from a BotPlanningStepSectionMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

BotPlanningStepSectionMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6103](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6103)

Verifies a BotPlanningStepSectionMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
