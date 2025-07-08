# Class: HandshakeMessage

Defined in: [WAProto/index.d.ts:15343](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15343)

Represents a HandshakeMessage.

## Implements

- [`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

## Constructors

### new HandshakeMessage()

> **new HandshakeMessage**(`properties`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:15349](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15349)

Constructs a new HandshakeMessage.

#### Parameters

##### properties?

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

Properties to set

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

## Properties

### clientFinish?

> `optional` **clientFinish**: `null` \| [`IClientFinish`](../namespaces/HandshakeMessage/interfaces/IClientFinish.md)

Defined in: [WAProto/index.d.ts:15358](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15358)

HandshakeMessage clientFinish.

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`clientFinish`](../interfaces/IHandshakeMessage.md#clientfinish)

***

### clientHello?

> `optional` **clientHello**: `null` \| [`IClientHello`](../namespaces/HandshakeMessage/interfaces/IClientHello.md)

Defined in: [WAProto/index.d.ts:15352](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15352)

HandshakeMessage clientHello.

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`clientHello`](../interfaces/IHandshakeMessage.md#clienthello)

***

### serverHello?

> `optional` **serverHello**: `null` \| [`IServerHello`](../namespaces/HandshakeMessage/interfaces/IServerHello.md)

Defined in: [WAProto/index.d.ts:15355](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15355)

HandshakeMessage serverHello.

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`serverHello`](../interfaces/IHandshakeMessage.md#serverhello)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15428](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15428)

Converts this HandshakeMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:15365](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15365)

Creates a new HandshakeMessage instance using the specified properties.

#### Parameters

##### properties?

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

Properties to set

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:15391](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15391)

Decodes a HandshakeMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:15400](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15400)

Decodes a HandshakeMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15373](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15373)

Encodes the specified HandshakeMessage message. Does not implicitly [verify](HandshakeMessage.md#verify) messages.

#### Parameters

##### message

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

HandshakeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15381](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15381)

Encodes the specified HandshakeMessage message, length delimited. Does not implicitly [verify](HandshakeMessage.md#verify) messages.

#### Parameters

##### message

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

HandshakeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:15414](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15414)

Creates a HandshakeMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:15435](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15435)

Gets the default type url for HandshakeMessage

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

Defined in: [WAProto/index.d.ts:15422](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15422)

Creates a plain object from a HandshakeMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`HandshakeMessage`](HandshakeMessage.md)

HandshakeMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15407](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L15407)

Verifies a HandshakeMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
