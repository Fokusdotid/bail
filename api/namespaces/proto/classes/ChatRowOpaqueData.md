# Class: ChatRowOpaqueData

Defined in: [WAProto/index.d.ts:8254](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8254)

Represents a ChatRowOpaqueData.

## Implements

- [`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

## Constructors

### new ChatRowOpaqueData()

> **new ChatRowOpaqueData**(`properties`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:8260](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8260)

Constructs a new ChatRowOpaqueData.

#### Parameters

##### properties?

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

Properties to set

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

## Properties

### draftMessage?

> `optional` **draftMessage**: `null` \| [`IDraftMessage`](../namespaces/ChatRowOpaqueData/interfaces/IDraftMessage.md)

Defined in: [WAProto/index.d.ts:8263](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8263)

ChatRowOpaqueData draftMessage.

#### Implementation of

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md).[`draftMessage`](../interfaces/IChatRowOpaqueData.md#draftmessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8333](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8333)

Converts this ChatRowOpaqueData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:8270](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8270)

Creates a new ChatRowOpaqueData instance using the specified properties.

#### Parameters

##### properties?

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

Properties to set

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:8296](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8296)

Decodes a ChatRowOpaqueData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:8305](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8305)

Decodes a ChatRowOpaqueData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8278](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8278)

Encodes the specified ChatRowOpaqueData message. Does not implicitly [verify](ChatRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

ChatRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8286](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8286)

Encodes the specified ChatRowOpaqueData message, length delimited. Does not implicitly [verify](ChatRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

ChatRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:8319](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8319)

Creates a ChatRowOpaqueData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8340](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8340)

Gets the default type url for ChatRowOpaqueData

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

Defined in: [WAProto/index.d.ts:8327](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8327)

Creates a plain object from a ChatRowOpaqueData message. Also converts values to other types if specified.

#### Parameters

##### message

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

ChatRowOpaqueData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8312](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L8312)

Verifies a ChatRowOpaqueData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
