# Class: PlaceholderMessageResendRequest

Defined in: [WAProto/index.d.ts:29618](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29618)

Represents a PlaceholderMessageResendRequest.

## Implements

- [`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

## Constructors

### new PlaceholderMessageResendRequest()

> **new PlaceholderMessageResendRequest**(`properties`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:29624](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29624)

Constructs a new PlaceholderMessageResendRequest.

#### Parameters

##### properties?

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

Properties to set

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

## Properties

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../../../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:29627](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29627)

PlaceholderMessageResendRequest messageKey.

#### Implementation of

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md).[`messageKey`](../interfaces/IPlaceholderMessageResendRequest.md#messagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29697](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29697)

Converts this PlaceholderMessageResendRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:29634](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29634)

Creates a new PlaceholderMessageResendRequest instance using the specified properties.

#### Parameters

##### properties?

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

Properties to set

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:29660](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29660)

Decodes a PlaceholderMessageResendRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:29669](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29669)

Decodes a PlaceholderMessageResendRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29642](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29642)

Encodes the specified PlaceholderMessageResendRequest message. Does not implicitly [verify](PlaceholderMessageResendRequest.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29650](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29650)

Encodes the specified PlaceholderMessageResendRequest message, length delimited. Does not implicitly [verify](PlaceholderMessageResendRequest.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:29683](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29683)

Creates a PlaceholderMessageResendRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:29704](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29704)

Gets the default type url for PlaceholderMessageResendRequest

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

Defined in: [WAProto/index.d.ts:29691](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29691)

Creates a plain object from a PlaceholderMessageResendRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

PlaceholderMessageResendRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29676](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L29676)

Verifies a PlaceholderMessageResendRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
