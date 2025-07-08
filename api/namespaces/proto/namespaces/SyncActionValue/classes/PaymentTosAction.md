# Class: PaymentTosAction

Defined in: [WAProto/index.d.ts:47378](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47378)

Represents a PaymentTosAction.

## Implements

- [`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

## Constructors

### new PaymentTosAction()

> **new PaymentTosAction**(`properties`?): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:47384](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47384)

Constructs a new PaymentTosAction.

#### Parameters

##### properties?

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

Properties to set

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

## Properties

### accepted

> **accepted**: `boolean`

Defined in: [WAProto/index.d.ts:47390](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47390)

PaymentTosAction accepted.

#### Implementation of

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md).[`accepted`](../interfaces/IPaymentTosAction.md#accepted)

***

### paymentNotice

> **paymentNotice**: [`BR_PAY_PRIVACY_POLICY`](../namespaces/PaymentTosAction/enumerations/PaymentNotice.md#br_pay_privacy_policy)

Defined in: [WAProto/index.d.ts:47387](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47387)

PaymentTosAction paymentNotice.

#### Implementation of

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md).[`paymentNotice`](../interfaces/IPaymentTosAction.md#paymentnotice)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:47460](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47460)

Converts this PaymentTosAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:47397](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47397)

Creates a new PaymentTosAction instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

Properties to set

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

PaymentTosAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:47423](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47423)

Decodes a PaymentTosAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

PaymentTosAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:47432](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47432)

Decodes a PaymentTosAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

PaymentTosAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47405](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47405)

Encodes the specified PaymentTosAction message. Does not implicitly [verify](PaymentTosAction.md#verify) messages.

#### Parameters

##### message

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

PaymentTosAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47413](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47413)

Encodes the specified PaymentTosAction message, length delimited. Does not implicitly [verify](PaymentTosAction.md#verify) messages.

#### Parameters

##### message

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

PaymentTosAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:47446](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47446)

Creates a PaymentTosAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

PaymentTosAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:47467](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47467)

Gets the default type url for PaymentTosAction

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

Defined in: [WAProto/index.d.ts:47454](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47454)

Creates a plain object from a PaymentTosAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentTosAction`](PaymentTosAction.md)

PaymentTosAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:47439](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L47439)

Verifies a PaymentTosAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
