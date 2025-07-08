# Class: EmbeddedMessage

Defined in: [WAProto/index.d.ts:13884](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13884)

Represents an EmbeddedMessage.

## Implements

- [`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

## Constructors

### new EmbeddedMessage()

> **new EmbeddedMessage**(`properties`?): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:13890](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13890)

Constructs a new EmbeddedMessage.

#### Parameters

##### properties?

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

Properties to set

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:13896](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13896)

EmbeddedMessage message.

#### Implementation of

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md).[`message`](../interfaces/IEmbeddedMessage.md#message)

***

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13893](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13893)

EmbeddedMessage stanzaId.

#### Implementation of

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md).[`stanzaId`](../interfaces/IEmbeddedMessage.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13966](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13966)

Converts this EmbeddedMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:13903](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13903)

Creates a new EmbeddedMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

Properties to set

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

EmbeddedMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:13929](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13929)

Decodes an EmbeddedMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

EmbeddedMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:13938](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13938)

Decodes an EmbeddedMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

EmbeddedMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13911](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13911)

Encodes the specified EmbeddedMessage message. Does not implicitly [verify](EmbeddedMessage.md#verify) messages.

#### Parameters

##### message

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

EmbeddedMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13919](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13919)

Encodes the specified EmbeddedMessage message, length delimited. Does not implicitly [verify](EmbeddedMessage.md#verify) messages.

#### Parameters

##### message

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

EmbeddedMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:13952](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13952)

Creates an EmbeddedMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

EmbeddedMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13973](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13973)

Gets the default type url for EmbeddedMessage

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

Defined in: [WAProto/index.d.ts:13960](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13960)

Creates a plain object from an EmbeddedMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EmbeddedMessage`](EmbeddedMessage.md)

EmbeddedMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13945](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L13945)

Verifies an EmbeddedMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
