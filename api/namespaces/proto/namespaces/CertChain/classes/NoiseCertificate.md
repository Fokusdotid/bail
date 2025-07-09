# Class: NoiseCertificate

Defined in: [WAProto/index.d.ts:7926](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7926)

Represents a NoiseCertificate.

## Implements

- [`INoiseCertificate`](../interfaces/INoiseCertificate.md)

## Constructors

### new NoiseCertificate()

> **new NoiseCertificate**(`properties`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:7932](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7932)

Constructs a new NoiseCertificate.

#### Parameters

##### properties?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

Properties to set

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

## Properties

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7935](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7935)

NoiseCertificate details.

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`details`](../interfaces/INoiseCertificate.md#details)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7938](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7938)

NoiseCertificate signature.

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`signature`](../interfaces/INoiseCertificate.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8008](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L8008)

Converts this NoiseCertificate to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:7945](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7945)

Creates a new NoiseCertificate instance using the specified properties.

#### Parameters

##### properties?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

Properties to set

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:7971](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7971)

Decodes a NoiseCertificate message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:7980](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7980)

Decodes a NoiseCertificate message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7953](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7953)

Encodes the specified NoiseCertificate message. Does not implicitly [verify](NoiseCertificate.md#verify) messages.

#### Parameters

##### message

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

NoiseCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7961](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7961)

Encodes the specified NoiseCertificate message, length delimited. Does not implicitly [verify](NoiseCertificate.md#verify) messages.

#### Parameters

##### message

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

NoiseCertificate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:7994](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7994)

Creates a NoiseCertificate message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8015](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L8015)

Gets the default type url for NoiseCertificate

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

Defined in: [WAProto/index.d.ts:8002](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L8002)

Creates a plain object from a NoiseCertificate message. Also converts values to other types if specified.

#### Parameters

##### message

[`NoiseCertificate`](NoiseCertificate.md)

NoiseCertificate

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7987](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7987)

Verifies a NoiseCertificate message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
