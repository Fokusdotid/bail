# Class: QuickReplyButton

Defined in: [WAProto/index.d.ts:51063](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51063)

Represents a QuickReplyButton.

## Implements

- [`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

## Constructors

### new QuickReplyButton()

> **new QuickReplyButton**(`properties`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:51069](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51069)

Constructs a new QuickReplyButton.

#### Parameters

##### properties?

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

Properties to set

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:51072](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51072)

QuickReplyButton displayText.

#### Implementation of

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md).[`displayText`](../interfaces/IQuickReplyButton.md#displaytext)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:51075](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51075)

QuickReplyButton id.

#### Implementation of

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md).[`id`](../interfaces/IQuickReplyButton.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51145](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51145)

Converts this QuickReplyButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:51082](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51082)

Creates a new QuickReplyButton instance using the specified properties.

#### Parameters

##### properties?

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

Properties to set

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:51108](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51108)

Decodes a QuickReplyButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:51117](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51117)

Decodes a QuickReplyButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51090](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51090)

Encodes the specified QuickReplyButton message. Does not implicitly [verify](QuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

QuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51098](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51098)

Encodes the specified QuickReplyButton message, length delimited. Does not implicitly [verify](QuickReplyButton.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

QuickReplyButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:51131](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51131)

Creates a QuickReplyButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51152](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51152)

Gets the default type url for QuickReplyButton

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

Defined in: [WAProto/index.d.ts:51139](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51139)

Creates a plain object from a QuickReplyButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`QuickReplyButton`](QuickReplyButton.md)

QuickReplyButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51124](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51124)

Verifies a QuickReplyButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
