# Class: HydratedQuickReplyButton

Defined in: [WAProto/index.d.ts:16312](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16312)

Represents a HydratedQuickReplyButton.

## Implements

- [`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

## Constructors

### new HydratedQuickReplyButton()

> **new HydratedQuickReplyButton**(`properties`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:16318](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16318)

Constructs a new HydratedQuickReplyButton.

#### Parameters

##### properties?

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

Properties to set

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16321](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16321)

HydratedQuickReplyButton displayText.

#### Implementation of

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md).[`displayText`](../interfaces/IHydratedQuickReplyButton.md#displaytext)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16324](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16324)

HydratedQuickReplyButton id.

#### Implementation of

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md).[`id`](../interfaces/IHydratedQuickReplyButton.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16394](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16394)

Converts this HydratedQuickReplyButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:16331](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16331)

Creates a new HydratedQuickReplyButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

Properties to set

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:16357](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16357)

Decodes a HydratedQuickReplyButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:16366](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16366)

Decodes a HydratedQuickReplyButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16339](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16339)

Encodes the specified HydratedQuickReplyButton message. Does not implicitly [verify](HydratedQuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

HydratedQuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16347](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16347)

Encodes the specified HydratedQuickReplyButton message, length delimited. Does not implicitly [verify](HydratedQuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

HydratedQuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:16380](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16380)

Creates a HydratedQuickReplyButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:16401](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16401)

Gets the default type url for HydratedQuickReplyButton

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

Defined in: [WAProto/index.d.ts:16388](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16388)

Creates a plain object from a HydratedQuickReplyButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

HydratedQuickReplyButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16373](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L16373)

Verifies a HydratedQuickReplyButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
