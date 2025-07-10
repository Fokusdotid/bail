# Class: VerifiedNameCertificate

Defined in: [WAProto/index.d.ts:51958](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51958)

Represents a VerifiedNameCertificate.

## Implements

- [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

## Constructors

### new VerifiedNameCertificate()

> **new VerifiedNameCertificate**(`properties`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:51964](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51964)

Constructs a new VerifiedNameCertificate.

#### Parameters

##### properties?

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Properties to set

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

## Properties

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:51967](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51967)

VerifiedNameCertificate details.

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`details`](../interfaces/IVerifiedNameCertificate.md#details)

***

### serverSignature?

> `optional` **serverSignature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:51973](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51973)

VerifiedNameCertificate serverSignature.

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`serverSignature`](../interfaces/IVerifiedNameCertificate.md#serversignature)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:51970](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51970)

VerifiedNameCertificate signature.

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`signature`](../interfaces/IVerifiedNameCertificate.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:52043](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L52043)

Converts this VerifiedNameCertificate to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:51980](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51980)

Creates a new VerifiedNameCertificate instance using the specified properties.

#### Parameters

##### properties?

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Properties to set

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:52006](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L52006)

Decodes a VerifiedNameCertificate message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:52015](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L52015)

Decodes a VerifiedNameCertificate message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51988](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51988)

Encodes the specified VerifiedNameCertificate message. Does not implicitly [verify](VerifiedNameCertificate.md#verify) messages.

#### Parameters

##### message

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

VerifiedNameCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51996](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51996)

Encodes the specified VerifiedNameCertificate message, length delimited. Does not implicitly [verify](VerifiedNameCertificate.md#verify) messages.

#### Parameters

##### message

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

VerifiedNameCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:52029](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L52029)

Creates a VerifiedNameCertificate message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:52050](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L52050)

Gets the default type url for VerifiedNameCertificate

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

Defined in: [WAProto/index.d.ts:52037](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L52037)

Creates a plain object from a VerifiedNameCertificate message. Also converts values to other types if specified.

#### Parameters

##### message

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

VerifiedNameCertificate

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:52022](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L52022)

Verifies a VerifiedNameCertificate message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
