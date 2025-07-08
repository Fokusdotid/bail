# Class: MerchantPaymentPartnerAction

Defined in: [WAProto/index.d.ts:46719](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46719)

Represents a MerchantPaymentPartnerAction.

## Implements

- [`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

## Constructors

### new MerchantPaymentPartnerAction()

> **new MerchantPaymentPartnerAction**(`properties`?): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:46725](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46725)

Constructs a new MerchantPaymentPartnerAction.

#### Parameters

##### properties?

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

Properties to set

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

## Properties

### country

> **country**: `string`

Defined in: [WAProto/index.d.ts:46731](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46731)

MerchantPaymentPartnerAction country.

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`country`](../interfaces/IMerchantPaymentPartnerAction.md#country)

***

### credentialId?

> `optional` **credentialId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46737](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46737)

MerchantPaymentPartnerAction credentialId.

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`credentialId`](../interfaces/IMerchantPaymentPartnerAction.md#credentialid)

***

### gatewayName?

> `optional` **gatewayName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46734](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46734)

MerchantPaymentPartnerAction gatewayName.

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`gatewayName`](../interfaces/IMerchantPaymentPartnerAction.md#gatewayname)

***

### status

> **status**: [`Status`](../namespaces/MerchantPaymentPartnerAction/enumerations/Status.md)

Defined in: [WAProto/index.d.ts:46728](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46728)

MerchantPaymentPartnerAction status.

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`status`](../interfaces/IMerchantPaymentPartnerAction.md#status)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:46807](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46807)

Converts this MerchantPaymentPartnerAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:46744](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46744)

Creates a new MerchantPaymentPartnerAction instance using the specified properties.

#### Parameters

##### properties?

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

Properties to set

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

MerchantPaymentPartnerAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:46770](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46770)

Decodes a MerchantPaymentPartnerAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

MerchantPaymentPartnerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:46779](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46779)

Decodes a MerchantPaymentPartnerAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

MerchantPaymentPartnerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46752](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46752)

Encodes the specified MerchantPaymentPartnerAction message. Does not implicitly [verify](MerchantPaymentPartnerAction.md#verify) messages.

#### Parameters

##### message

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

MerchantPaymentPartnerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46760](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46760)

Encodes the specified MerchantPaymentPartnerAction message, length delimited. Does not implicitly [verify](MerchantPaymentPartnerAction.md#verify) messages.

#### Parameters

##### message

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

MerchantPaymentPartnerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:46793](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46793)

Creates a MerchantPaymentPartnerAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

MerchantPaymentPartnerAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:46814](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46814)

Gets the default type url for MerchantPaymentPartnerAction

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

Defined in: [WAProto/index.d.ts:46801](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46801)

Creates a plain object from a MerchantPaymentPartnerAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

MerchantPaymentPartnerAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:46786](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L46786)

Verifies a MerchantPaymentPartnerAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
