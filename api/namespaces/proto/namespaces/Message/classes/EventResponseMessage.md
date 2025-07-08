# Class: EventResponseMessage

Defined in: [WAProto/index.d.ts:22919](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22919)

Represents an EventResponseMessage.

## Implements

- [`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

## Constructors

### new EventResponseMessage()

> **new EventResponseMessage**(`properties`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22925](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22925)

Constructs a new EventResponseMessage.

#### Parameters

##### properties?

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

Properties to set

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

## Properties

### extraGuestCount?

> `optional` **extraGuestCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:22934](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22934)

EventResponseMessage extraGuestCount.

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`extraGuestCount`](../interfaces/IEventResponseMessage.md#extraguestcount)

***

### response?

> `optional` **response**: `null` \| [`EventResponseType`](../namespaces/EventResponseMessage/enumerations/EventResponseType.md)

Defined in: [WAProto/index.d.ts:22928](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22928)

EventResponseMessage response.

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`response`](../interfaces/IEventResponseMessage.md#response)

***

### timestampMs?

> `optional` **timestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:22931](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22931)

EventResponseMessage timestampMs.

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`timestampMs`](../interfaces/IEventResponseMessage.md#timestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23004](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L23004)

Converts this EventResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22941](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22941)

Creates a new EventResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

Properties to set

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22967](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22967)

Decodes an EventResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22976](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22976)

Decodes an EventResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22949](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22949)

Encodes the specified EventResponseMessage message. Does not implicitly [verify](EventResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

EventResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22957](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22957)

Encodes the specified EventResponseMessage message, length delimited. Does not implicitly [verify](EventResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

EventResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:22990](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22990)

Creates an EventResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:23011](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L23011)

Gets the default type url for EventResponseMessage

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

Defined in: [WAProto/index.d.ts:22998](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22998)

Creates a plain object from an EventResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EventResponseMessage`](EventResponseMessage.md)

EventResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22983](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L22983)

Verifies an EventResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
