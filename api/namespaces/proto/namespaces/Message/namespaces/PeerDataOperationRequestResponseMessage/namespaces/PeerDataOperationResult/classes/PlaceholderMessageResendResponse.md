# Class: PlaceholderMessageResendResponse

Defined in: [WAProto/index.d.ts:30751](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30751)

Represents a PlaceholderMessageResendResponse.

## Implements

- [`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

## Constructors

### new PlaceholderMessageResendResponse()

> **new PlaceholderMessageResendResponse**(`properties`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:30757](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30757)

Constructs a new PlaceholderMessageResendResponse.

#### Parameters

##### properties?

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

Properties to set

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

## Properties

### webMessageInfoBytes?

> `optional` **webMessageInfoBytes**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:30760](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30760)

PlaceholderMessageResendResponse webMessageInfoBytes.

#### Implementation of

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md).[`webMessageInfoBytes`](../interfaces/IPlaceholderMessageResendResponse.md#webmessageinfobytes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30830](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30830)

Converts this PlaceholderMessageResendResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:30767](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30767)

Creates a new PlaceholderMessageResendResponse instance using the specified properties.

#### Parameters

##### properties?

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

Properties to set

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:30793](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30793)

Decodes a PlaceholderMessageResendResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:30802](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30802)

Decodes a PlaceholderMessageResendResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30775](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30775)

Encodes the specified PlaceholderMessageResendResponse message. Does not implicitly [verify](PlaceholderMessageResendResponse.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30783](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30783)

Encodes the specified PlaceholderMessageResendResponse message, length delimited. Does not implicitly [verify](PlaceholderMessageResendResponse.md#verify) messages.

#### Parameters

##### message

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:30816](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30816)

Creates a PlaceholderMessageResendResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:30837](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30837)

Gets the default type url for PlaceholderMessageResendResponse

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

Defined in: [WAProto/index.d.ts:30824](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30824)

Creates a plain object from a PlaceholderMessageResendResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

PlaceholderMessageResendResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30809](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30809)

Verifies a PlaceholderMessageResendResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
