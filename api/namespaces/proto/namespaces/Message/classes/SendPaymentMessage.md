# Class: SendPaymentMessage

Defined in: [WAProto/index.d.ts:33655](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33655)

Represents a SendPaymentMessage.

## Implements

- [`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

## Constructors

### new SendPaymentMessage()

> **new SendPaymentMessage**(`properties`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:33661](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33661)

Constructs a new SendPaymentMessage.

#### Parameters

##### properties?

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

Properties to set

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

## Properties

### background?

> `optional` **background**: `null` \| [`IPaymentBackground`](../../../interfaces/IPaymentBackground.md)

Defined in: [WAProto/index.d.ts:33670](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33670)

SendPaymentMessage background.

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`background`](../interfaces/ISendPaymentMessage.md#background)

***

### noteMessage?

> `optional` **noteMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:33664](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33664)

SendPaymentMessage noteMessage.

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`noteMessage`](../interfaces/ISendPaymentMessage.md#notemessage)

***

### requestMessageKey?

> `optional` **requestMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:33667](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33667)

SendPaymentMessage requestMessageKey.

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`requestMessageKey`](../interfaces/ISendPaymentMessage.md#requestmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33740](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33740)

Converts this SendPaymentMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:33677](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33677)

Creates a new SendPaymentMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

Properties to set

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:33703](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33703)

Decodes a SendPaymentMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:33712](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33712)

Decodes a SendPaymentMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33685](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33685)

Encodes the specified SendPaymentMessage message. Does not implicitly [verify](SendPaymentMessage.md#verify) messages.

#### Parameters

##### message

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

SendPaymentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33693](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33693)

Encodes the specified SendPaymentMessage message, length delimited. Does not implicitly [verify](SendPaymentMessage.md#verify) messages.

#### Parameters

##### message

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

SendPaymentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:33726](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33726)

Creates a SendPaymentMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:33747](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33747)

Gets the default type url for SendPaymentMessage

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

Defined in: [WAProto/index.d.ts:33734](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33734)

Creates a plain object from a SendPaymentMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SendPaymentMessage`](SendPaymentMessage.md)

SendPaymentMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33719](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33719)

Verifies a SendPaymentMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
