# Class: PaymentLinkButton

Defined in: [WAProto/index.d.ts:29049](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29049)

Represents a PaymentLinkButton.

## Implements

- [`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

## Constructors

### new PaymentLinkButton()

> **new PaymentLinkButton**(`properties`?): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:29055](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29055)

Constructs a new PaymentLinkButton.

#### Parameters

##### properties?

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

Properties to set

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:29058](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29058)

PaymentLinkButton displayText.

#### Implementation of

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md).[`displayText`](../interfaces/IPaymentLinkButton.md#displaytext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29128](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29128)

Converts this PaymentLinkButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:29065](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29065)

Creates a new PaymentLinkButton instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

Properties to set

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

PaymentLinkButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:29091](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29091)

Decodes a PaymentLinkButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

PaymentLinkButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:29100](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29100)

Decodes a PaymentLinkButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

PaymentLinkButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29073](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29073)

Encodes the specified PaymentLinkButton message. Does not implicitly [verify](PaymentLinkButton.md#verify) messages.

#### Parameters

##### message

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

PaymentLinkButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29081](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29081)

Encodes the specified PaymentLinkButton message, length delimited. Does not implicitly [verify](PaymentLinkButton.md#verify) messages.

#### Parameters

##### message

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

PaymentLinkButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:29114](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29114)

Creates a PaymentLinkButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

PaymentLinkButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:29135](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29135)

Gets the default type url for PaymentLinkButton

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

Defined in: [WAProto/index.d.ts:29122](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29122)

Creates a plain object from a PaymentLinkButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentLinkButton`](PaymentLinkButton.md)

PaymentLinkButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29107](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L29107)

Verifies a PaymentLinkButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
