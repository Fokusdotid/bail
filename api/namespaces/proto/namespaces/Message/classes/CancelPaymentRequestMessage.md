# Class: CancelPaymentRequestMessage

Defined in: [WAProto/index.d.ts:21257](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21257)

Represents a CancelPaymentRequestMessage.

## Implements

- [`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

## Constructors

### new CancelPaymentRequestMessage()

> **new CancelPaymentRequestMessage**(`properties`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:21263](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21263)

Constructs a new CancelPaymentRequestMessage.

#### Parameters

##### properties?

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

Properties to set

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:21266](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21266)

CancelPaymentRequestMessage key.

#### Implementation of

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md).[`key`](../interfaces/ICancelPaymentRequestMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21336](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21336)

Converts this CancelPaymentRequestMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:21273](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21273)

Creates a new CancelPaymentRequestMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

Properties to set

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:21299](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21299)

Decodes a CancelPaymentRequestMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:21308](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21308)

Decodes a CancelPaymentRequestMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21281](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21281)

Encodes the specified CancelPaymentRequestMessage message. Does not implicitly [verify](CancelPaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

CancelPaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21289](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21289)

Encodes the specified CancelPaymentRequestMessage message, length delimited. Does not implicitly [verify](CancelPaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

CancelPaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:21322](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21322)

Creates a CancelPaymentRequestMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21343](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21343)

Gets the default type url for CancelPaymentRequestMessage

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

Defined in: [WAProto/index.d.ts:21330](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21330)

Creates a plain object from a CancelPaymentRequestMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

CancelPaymentRequestMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21315](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21315)

Verifies a CancelPaymentRequestMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
