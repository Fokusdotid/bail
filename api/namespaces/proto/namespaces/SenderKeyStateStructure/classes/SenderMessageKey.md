# Class: SenderMessageKey

Defined in: [WAProto/index.d.ts:41485](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41485)

Represents a SenderMessageKey.

## Implements

- [`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

## Constructors

### new SenderMessageKey()

> **new SenderMessageKey**(`properties`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:41491](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41491)

Constructs a new SenderMessageKey.

#### Parameters

##### properties?

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

Properties to set

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

## Properties

### iteration?

> `optional` **iteration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:41494](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41494)

SenderMessageKey iteration.

#### Implementation of

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md).[`iteration`](../interfaces/ISenderMessageKey.md#iteration)

***

### seed?

> `optional` **seed**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41497](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41497)

SenderMessageKey seed.

#### Implementation of

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md).[`seed`](../interfaces/ISenderMessageKey.md#seed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:41567](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41567)

Converts this SenderMessageKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:41504](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41504)

Creates a new SenderMessageKey instance using the specified properties.

#### Parameters

##### properties?

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

Properties to set

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:41530](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41530)

Decodes a SenderMessageKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:41539](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41539)

Decodes a SenderMessageKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41512](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41512)

Encodes the specified SenderMessageKey message. Does not implicitly [verify](SenderMessageKey.md#verify) messages.

#### Parameters

##### message

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

SenderMessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41520](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41520)

Encodes the specified SenderMessageKey message, length delimited. Does not implicitly [verify](SenderMessageKey.md#verify) messages.

#### Parameters

##### message

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

SenderMessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:41553](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41553)

Creates a SenderMessageKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:41574](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41574)

Gets the default type url for SenderMessageKey

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

Defined in: [WAProto/index.d.ts:41561](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41561)

Creates a plain object from a SenderMessageKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderMessageKey`](SenderMessageKey.md)

SenderMessageKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:41546](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L41546)

Verifies a SenderMessageKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
