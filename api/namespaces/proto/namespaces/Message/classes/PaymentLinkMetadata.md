# Class: PaymentLinkMetadata

Defined in: [WAProto/index.d.ts:28947](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28947)

Represents a PaymentLinkMetadata.

## Implements

- [`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

## Constructors

### new PaymentLinkMetadata()

> **new PaymentLinkMetadata**(`properties`?): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:28953](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28953)

Constructs a new PaymentLinkMetadata.

#### Parameters

##### properties?

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

Properties to set

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

## Properties

### button?

> `optional` **button**: `null` \| [`IPaymentLinkButton`](../namespaces/PaymentLinkMetadata/interfaces/IPaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:28956](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28956)

PaymentLinkMetadata button.

#### Implementation of

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md).[`button`](../interfaces/IPaymentLinkMetadata.md#button)

***

### header?

> `optional` **header**: `null` \| [`IPaymentLinkHeader`](../namespaces/PaymentLinkMetadata/interfaces/IPaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:28959](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28959)

PaymentLinkMetadata header.

#### Implementation of

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md).[`header`](../interfaces/IPaymentLinkMetadata.md#header)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29029](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L29029)

Converts this PaymentLinkMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:28966](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28966)

Creates a new PaymentLinkMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

Properties to set

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

PaymentLinkMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:28992](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28992)

Decodes a PaymentLinkMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

PaymentLinkMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:29001](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L29001)

Decodes a PaymentLinkMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

PaymentLinkMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28974](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28974)

Encodes the specified PaymentLinkMetadata message. Does not implicitly [verify](PaymentLinkMetadata.md#verify) messages.

#### Parameters

##### message

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

PaymentLinkMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28982](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L28982)

Encodes the specified PaymentLinkMetadata message, length delimited. Does not implicitly [verify](PaymentLinkMetadata.md#verify) messages.

#### Parameters

##### message

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

PaymentLinkMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:29015](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L29015)

Creates a PaymentLinkMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

PaymentLinkMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:29036](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L29036)

Gets the default type url for PaymentLinkMetadata

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

Defined in: [WAProto/index.d.ts:29023](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L29023)

Creates a plain object from a PaymentLinkMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

PaymentLinkMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29008](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L29008)

Verifies a PaymentLinkMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
