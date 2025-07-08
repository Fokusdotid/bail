# Class: URLButton

Defined in: [WAProto/index.d.ts:51166](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51166)

Represents a URLButton.

## Implements

- [`IURLButton`](../interfaces/IURLButton.md)

## Constructors

### new URLButton()

> **new URLButton**(`properties`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:51172](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51172)

Constructs a new URLButton.

#### Parameters

##### properties?

[`IURLButton`](../interfaces/IURLButton.md)

Properties to set

#### Returns

[`URLButton`](URLButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:51175](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51175)

URLButton displayText.

#### Implementation of

[`IURLButton`](../interfaces/IURLButton.md).[`displayText`](../interfaces/IURLButton.md#displaytext)

***

### url?

> `optional` **url**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:51178](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51178)

URLButton url.

#### Implementation of

[`IURLButton`](../interfaces/IURLButton.md).[`url`](../interfaces/IURLButton.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51248](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51248)

Converts this URLButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:51185](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51185)

Creates a new URLButton instance using the specified properties.

#### Parameters

##### properties?

[`IURLButton`](../interfaces/IURLButton.md)

Properties to set

#### Returns

[`URLButton`](URLButton.md)

URLButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:51211](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51211)

Decodes a URLButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`URLButton`](URLButton.md)

URLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:51220](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51220)

Decodes a URLButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`URLButton`](URLButton.md)

URLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51193](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51193)

Encodes the specified URLButton message. Does not implicitly [verify](URLButton.md#verify) messages.

#### Parameters

##### message

[`IURLButton`](../interfaces/IURLButton.md)

URLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51201](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51201)

Encodes the specified URLButton message, length delimited. Does not implicitly [verify](URLButton.md#verify) messages.

#### Parameters

##### message

[`IURLButton`](../interfaces/IURLButton.md)

URLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:51234](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51234)

Creates a URLButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`URLButton`](URLButton.md)

URLButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51255](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51255)

Gets the default type url for URLButton

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

Defined in: [WAProto/index.d.ts:51242](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51242)

Creates a plain object from a URLButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`URLButton`](URLButton.md)

URLButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51227](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L51227)

Verifies a URLButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
