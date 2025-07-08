# Class: PaymentInfoAction

Defined in: [WAProto/index.d.ts:47278](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47278)

Represents a PaymentInfoAction.

## Implements

- [`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

## Constructors

### new PaymentInfoAction()

> **new PaymentInfoAction**(`properties`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:47284](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47284)

Constructs a new PaymentInfoAction.

#### Parameters

##### properties?

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

Properties to set

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

## Properties

### cpi?

> `optional` **cpi**: `null` \| `string`

Defined in: [WAProto/index.d.ts:47287](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47287)

PaymentInfoAction cpi.

#### Implementation of

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md).[`cpi`](../interfaces/IPaymentInfoAction.md#cpi)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:47357](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47357)

Converts this PaymentInfoAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:47294](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47294)

Creates a new PaymentInfoAction instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

Properties to set

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:47320](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47320)

Decodes a PaymentInfoAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:47329](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47329)

Decodes a PaymentInfoAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47302](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47302)

Encodes the specified PaymentInfoAction message. Does not implicitly [verify](PaymentInfoAction.md#verify) messages.

#### Parameters

##### message

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

PaymentInfoAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47310](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47310)

Encodes the specified PaymentInfoAction message, length delimited. Does not implicitly [verify](PaymentInfoAction.md#verify) messages.

#### Parameters

##### message

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

PaymentInfoAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:47343](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47343)

Creates a PaymentInfoAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:47364](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47364)

Gets the default type url for PaymentInfoAction

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

Defined in: [WAProto/index.d.ts:47351](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47351)

Creates a plain object from a PaymentInfoAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentInfoAction`](PaymentInfoAction.md)

PaymentInfoAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:47336](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47336)

Verifies a PaymentInfoAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
