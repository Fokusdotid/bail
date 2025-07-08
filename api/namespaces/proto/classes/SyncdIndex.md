# Class: SyncdIndex

Defined in: [WAProto/index.d.ts:49865](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49865)

Represents a SyncdIndex.

## Implements

- [`ISyncdIndex`](../interfaces/ISyncdIndex.md)

## Constructors

### new SyncdIndex()

> **new SyncdIndex**(`properties`?): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:49871](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49871)

Constructs a new SyncdIndex.

#### Parameters

##### properties?

[`ISyncdIndex`](../interfaces/ISyncdIndex.md)

Properties to set

#### Returns

[`SyncdIndex`](SyncdIndex.md)

## Properties

### blob?

> `optional` **blob**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:49874](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49874)

SyncdIndex blob.

#### Implementation of

[`ISyncdIndex`](../interfaces/ISyncdIndex.md).[`blob`](../interfaces/ISyncdIndex.md#blob)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:49944](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49944)

Converts this SyncdIndex to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:49881](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49881)

Creates a new SyncdIndex instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdIndex`](../interfaces/ISyncdIndex.md)

Properties to set

#### Returns

[`SyncdIndex`](SyncdIndex.md)

SyncdIndex instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:49907](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49907)

Decodes a SyncdIndex message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdIndex`](SyncdIndex.md)

SyncdIndex

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:49916](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49916)

Decodes a SyncdIndex message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdIndex`](SyncdIndex.md)

SyncdIndex

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49889](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49889)

Encodes the specified SyncdIndex message. Does not implicitly [verify](SyncdIndex.md#verify) messages.

#### Parameters

##### message

[`ISyncdIndex`](../interfaces/ISyncdIndex.md)

SyncdIndex message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49897](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49897)

Encodes the specified SyncdIndex message, length delimited. Does not implicitly [verify](SyncdIndex.md#verify) messages.

#### Parameters

##### message

[`ISyncdIndex`](../interfaces/ISyncdIndex.md)

SyncdIndex message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:49930](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49930)

Creates a SyncdIndex message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdIndex`](SyncdIndex.md)

SyncdIndex

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:49951](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49951)

Gets the default type url for SyncdIndex

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

Defined in: [WAProto/index.d.ts:49938](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49938)

Creates a plain object from a SyncdIndex message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdIndex`](SyncdIndex.md)

SyncdIndex

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:49923](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L49923)

Verifies a SyncdIndex message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
