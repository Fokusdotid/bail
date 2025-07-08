# Class: BotAgeCollectionMetadata

Defined in: [WAProto/index.d.ts:3635](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3635)

Represents a BotAgeCollectionMetadata.

## Implements

- [`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

## Constructors

### new BotAgeCollectionMetadata()

> **new BotAgeCollectionMetadata**(`properties`?): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:3641](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3641)

Constructs a new BotAgeCollectionMetadata.

#### Parameters

##### properties?

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

Properties to set

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

## Properties

### ageCollectionEligible?

> `optional` **ageCollectionEligible**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3644](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3644)

BotAgeCollectionMetadata ageCollectionEligible.

#### Implementation of

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md).[`ageCollectionEligible`](../interfaces/IBotAgeCollectionMetadata.md#agecollectioneligible)

***

### shouldTriggerAgeCollectionOnClient?

> `optional` **shouldTriggerAgeCollectionOnClient**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3647](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3647)

BotAgeCollectionMetadata shouldTriggerAgeCollectionOnClient.

#### Implementation of

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md).[`shouldTriggerAgeCollectionOnClient`](../interfaces/IBotAgeCollectionMetadata.md#shouldtriggeragecollectiononclient)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3717](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3717)

Converts this BotAgeCollectionMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:3654](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3654)

Creates a new BotAgeCollectionMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

Properties to set

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

BotAgeCollectionMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:3680](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3680)

Decodes a BotAgeCollectionMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

BotAgeCollectionMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:3689](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3689)

Decodes a BotAgeCollectionMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

BotAgeCollectionMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3662](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3662)

Encodes the specified BotAgeCollectionMetadata message. Does not implicitly [verify](BotAgeCollectionMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

BotAgeCollectionMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3670](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3670)

Encodes the specified BotAgeCollectionMetadata message, length delimited. Does not implicitly [verify](BotAgeCollectionMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

BotAgeCollectionMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:3703](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3703)

Creates a BotAgeCollectionMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

BotAgeCollectionMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3724](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3724)

Gets the default type url for BotAgeCollectionMetadata

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

Defined in: [WAProto/index.d.ts:3711](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3711)

Creates a plain object from a BotAgeCollectionMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

BotAgeCollectionMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3696](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L3696)

Verifies a BotAgeCollectionMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
