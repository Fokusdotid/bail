# Class: PollAdditionalMetadata

Defined in: [WAProto/index.d.ts:39282](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39282)

Represents a PollAdditionalMetadata.

## Implements

- [`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

## Constructors

### new PollAdditionalMetadata()

> **new PollAdditionalMetadata**(`properties`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:39288](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39288)

Constructs a new PollAdditionalMetadata.

#### Parameters

##### properties?

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

Properties to set

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

## Properties

### pollInvalidated?

> `optional` **pollInvalidated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:39291](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39291)

PollAdditionalMetadata pollInvalidated.

#### Implementation of

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md).[`pollInvalidated`](../interfaces/IPollAdditionalMetadata.md#pollinvalidated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:39361](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39361)

Converts this PollAdditionalMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:39298](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39298)

Creates a new PollAdditionalMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

Properties to set

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:39324](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39324)

Decodes a PollAdditionalMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:39333](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39333)

Decodes a PollAdditionalMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39306](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39306)

Encodes the specified PollAdditionalMetadata message. Does not implicitly [verify](PollAdditionalMetadata.md#verify) messages.

#### Parameters

##### message

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

PollAdditionalMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39314](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39314)

Encodes the specified PollAdditionalMetadata message, length delimited. Does not implicitly [verify](PollAdditionalMetadata.md#verify) messages.

#### Parameters

##### message

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

PollAdditionalMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:39347](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39347)

Creates a PollAdditionalMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:39368](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39368)

Gets the default type url for PollAdditionalMetadata

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

Defined in: [WAProto/index.d.ts:39355](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39355)

Creates a plain object from a PollAdditionalMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

PollAdditionalMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:39340](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39340)

Verifies a PollAdditionalMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
