# Class: DeclinePaymentRequestMessage

Defined in: [WAProto/index.d.ts:22012](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22012)

Represents a DeclinePaymentRequestMessage.

## Implements

- [`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

## Constructors

### new DeclinePaymentRequestMessage()

> **new DeclinePaymentRequestMessage**(`properties`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:22018](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22018)

Constructs a new DeclinePaymentRequestMessage.

#### Parameters

##### properties?

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

Properties to set

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:22021](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22021)

DeclinePaymentRequestMessage key.

#### Implementation of

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md).[`key`](../interfaces/IDeclinePaymentRequestMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22091](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22091)

Converts this DeclinePaymentRequestMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:22028](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22028)

Creates a new DeclinePaymentRequestMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

Properties to set

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:22054](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22054)

Decodes a DeclinePaymentRequestMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:22063](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22063)

Decodes a DeclinePaymentRequestMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22036](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22036)

Encodes the specified DeclinePaymentRequestMessage message. Does not implicitly [verify](DeclinePaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22044](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22044)

Encodes the specified DeclinePaymentRequestMessage message, length delimited. Does not implicitly [verify](DeclinePaymentRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:22077](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22077)

Creates a DeclinePaymentRequestMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:22098](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22098)

Gets the default type url for DeclinePaymentRequestMessage

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

Defined in: [WAProto/index.d.ts:22085](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22085)

Creates a plain object from a DeclinePaymentRequestMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

DeclinePaymentRequestMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22070](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22070)

Verifies a DeclinePaymentRequestMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
