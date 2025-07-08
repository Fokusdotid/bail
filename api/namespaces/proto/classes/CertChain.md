# Class: CertChain

Defined in: [WAProto/index.d.ts:7821](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7821)

Represents a CertChain.

## Implements

- [`ICertChain`](../interfaces/ICertChain.md)

## Constructors

### new CertChain()

> **new CertChain**(`properties`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:7827](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7827)

Constructs a new CertChain.

#### Parameters

##### properties?

[`ICertChain`](../interfaces/ICertChain.md)

Properties to set

#### Returns

[`CertChain`](CertChain.md)

## Properties

### intermediate?

> `optional` **intermediate**: `null` \| [`INoiseCertificate`](../namespaces/CertChain/interfaces/INoiseCertificate.md)

Defined in: [WAProto/index.d.ts:7833](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7833)

CertChain intermediate.

#### Implementation of

[`ICertChain`](../interfaces/ICertChain.md).[`intermediate`](../interfaces/ICertChain.md#intermediate)

***

### leaf?

> `optional` **leaf**: `null` \| [`INoiseCertificate`](../namespaces/CertChain/interfaces/INoiseCertificate.md)

Defined in: [WAProto/index.d.ts:7830](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7830)

CertChain leaf.

#### Implementation of

[`ICertChain`](../interfaces/ICertChain.md).[`leaf`](../interfaces/ICertChain.md#leaf)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7903](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7903)

Converts this CertChain to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:7840](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7840)

Creates a new CertChain instance using the specified properties.

#### Parameters

##### properties?

[`ICertChain`](../interfaces/ICertChain.md)

Properties to set

#### Returns

[`CertChain`](CertChain.md)

CertChain instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:7866](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7866)

Decodes a CertChain message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CertChain`](CertChain.md)

CertChain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:7875](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7875)

Decodes a CertChain message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CertChain`](CertChain.md)

CertChain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7848](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7848)

Encodes the specified CertChain message. Does not implicitly [verify](CertChain.md#verify) messages.

#### Parameters

##### message

[`ICertChain`](../interfaces/ICertChain.md)

CertChain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7856](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7856)

Encodes the specified CertChain message, length delimited. Does not implicitly [verify](CertChain.md#verify) messages.

#### Parameters

##### message

[`ICertChain`](../interfaces/ICertChain.md)

CertChain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:7889](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7889)

Creates a CertChain message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CertChain`](CertChain.md)

CertChain

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7910](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7910)

Gets the default type url for CertChain

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

Defined in: [WAProto/index.d.ts:7897](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7897)

Creates a plain object from a CertChain message. Also converts values to other types if specified.

#### Parameters

##### message

[`CertChain`](CertChain.md)

CertChain

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7882](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L7882)

Verifies a CertChain message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
