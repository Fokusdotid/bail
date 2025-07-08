# Class: MessageSecretMessage

Defined in: [WAProto/index.d.ts:36261](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36261)

Represents a MessageSecretMessage.

## Implements

- [`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

## Constructors

### new MessageSecretMessage()

> **new MessageSecretMessage**(`properties`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:36267](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36267)

Constructs a new MessageSecretMessage.

#### Parameters

##### properties?

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

Properties to set

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:36273](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36273)

MessageSecretMessage encIv.

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`encIv`](../interfaces/IMessageSecretMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:36276](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36276)

MessageSecretMessage encPayload.

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`encPayload`](../interfaces/IMessageSecretMessage.md#encpayload)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:36270](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36270)

MessageSecretMessage version.

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`version`](../interfaces/IMessageSecretMessage.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:36346](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36346)

Converts this MessageSecretMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:36283](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36283)

Creates a new MessageSecretMessage instance using the specified properties.

#### Parameters

##### properties?

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

Properties to set

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:36309](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36309)

Decodes a MessageSecretMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:36318](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36318)

Decodes a MessageSecretMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36291](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36291)

Encodes the specified MessageSecretMessage message. Does not implicitly [verify](MessageSecretMessage.md#verify) messages.

#### Parameters

##### message

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

MessageSecretMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36299](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36299)

Encodes the specified MessageSecretMessage message, length delimited. Does not implicitly [verify](MessageSecretMessage.md#verify) messages.

#### Parameters

##### message

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

MessageSecretMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:36332](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36332)

Creates a MessageSecretMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:36353](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36353)

Gets the default type url for MessageSecretMessage

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

Defined in: [WAProto/index.d.ts:36340](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36340)

Creates a plain object from a MessageSecretMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageSecretMessage`](MessageSecretMessage.md)

MessageSecretMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:36325](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L36325)

Verifies a MessageSecretMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
