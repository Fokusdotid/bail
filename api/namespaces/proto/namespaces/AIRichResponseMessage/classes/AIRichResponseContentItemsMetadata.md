# Class: AIRichResponseContentItemsMetadata

Defined in: [WAProto/index.d.ts:1037](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1037)

Represents a AIRichResponseContentItemsMetadata.

## Implements

- [`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

## Constructors

### new AIRichResponseContentItemsMetadata()

> **new AIRichResponseContentItemsMetadata**(`properties`?): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:1043](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1043)

Constructs a new AIRichResponseContentItemsMetadata.

#### Parameters

##### properties?

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

Properties to set

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

## Properties

### contentType?

> `optional` **contentType**: `null` \| [`ContentType`](../namespaces/AIRichResponseContentItemsMetadata/enumerations/ContentType.md)

Defined in: [WAProto/index.d.ts:1049](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1049)

AIRichResponseContentItemsMetadata contentType.

#### Implementation of

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md).[`contentType`](../interfaces/IAIRichResponseContentItemsMetadata.md#contenttype)

***

### itemsMetadata

> **itemsMetadata**: [`IAIRichResponseContentItemMetadata`](../namespaces/AIRichResponseContentItemsMetadata/interfaces/IAIRichResponseContentItemMetadata.md)[]

Defined in: [WAProto/index.d.ts:1046](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1046)

AIRichResponseContentItemsMetadata itemsMetadata.

#### Implementation of

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md).[`itemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md#itemsmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1119](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1119)

Converts this AIRichResponseContentItemsMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:1056](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1056)

Creates a new AIRichResponseContentItemsMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

Properties to set

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

AIRichResponseContentItemsMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:1082](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1082)

Decodes a AIRichResponseContentItemsMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

AIRichResponseContentItemsMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:1091](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1091)

Decodes a AIRichResponseContentItemsMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

AIRichResponseContentItemsMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1064](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1064)

Encodes the specified AIRichResponseContentItemsMetadata message. Does not implicitly [verify](AIRichResponseContentItemsMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

AIRichResponseContentItemsMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1072](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1072)

Encodes the specified AIRichResponseContentItemsMetadata message, length delimited. Does not implicitly [verify](AIRichResponseContentItemsMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

AIRichResponseContentItemsMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:1105](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1105)

Creates a AIRichResponseContentItemsMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

AIRichResponseContentItemsMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1126](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1126)

Gets the default type url for AIRichResponseContentItemsMetadata

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

Defined in: [WAProto/index.d.ts:1113](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1113)

Creates a plain object from a AIRichResponseContentItemsMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

AIRichResponseContentItemsMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1098](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L1098)

Verifies a AIRichResponseContentItemsMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
