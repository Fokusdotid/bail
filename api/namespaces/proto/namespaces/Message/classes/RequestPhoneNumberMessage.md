# Class: RequestPhoneNumberMessage

Defined in: [WAProto/index.d.ts:33090](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33090)

Represents a RequestPhoneNumberMessage.

## Implements

- [`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

## Constructors

### new RequestPhoneNumberMessage()

> **new RequestPhoneNumberMessage**(`properties`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:33096](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33096)

Constructs a new RequestPhoneNumberMessage.

#### Parameters

##### properties?

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

Properties to set

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:33099](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33099)

RequestPhoneNumberMessage contextInfo.

#### Implementation of

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md).[`contextInfo`](../interfaces/IRequestPhoneNumberMessage.md#contextinfo)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33169](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33169)

Converts this RequestPhoneNumberMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:33106](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33106)

Creates a new RequestPhoneNumberMessage instance using the specified properties.

#### Parameters

##### properties?

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

Properties to set

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:33132](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33132)

Decodes a RequestPhoneNumberMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:33141](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33141)

Decodes a RequestPhoneNumberMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33114](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33114)

Encodes the specified RequestPhoneNumberMessage message. Does not implicitly [verify](RequestPhoneNumberMessage.md#verify) messages.

#### Parameters

##### message

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

RequestPhoneNumberMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33122](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33122)

Encodes the specified RequestPhoneNumberMessage message, length delimited. Does not implicitly [verify](RequestPhoneNumberMessage.md#verify) messages.

#### Parameters

##### message

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

RequestPhoneNumberMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:33155](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33155)

Creates a RequestPhoneNumberMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:33176](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33176)

Gets the default type url for RequestPhoneNumberMessage

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

Defined in: [WAProto/index.d.ts:33163](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33163)

Creates a plain object from a RequestPhoneNumberMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

RequestPhoneNumberMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33148](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L33148)

Verifies a RequestPhoneNumberMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
