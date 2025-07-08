# Class: SyncdSnapshot

Defined in: [WAProto/index.d.ts:50434](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50434)

Represents a SyncdSnapshot.

## Implements

- [`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

## Constructors

### new SyncdSnapshot()

> **new SyncdSnapshot**(`properties`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:50440](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50440)

Constructs a new SyncdSnapshot.

#### Parameters

##### properties?

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

Properties to set

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

## Properties

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:50452](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50452)

SyncdSnapshot keyId.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`keyId`](../interfaces/ISyncdSnapshot.md#keyid)

***

### mac?

> `optional` **mac**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:50449](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50449)

SyncdSnapshot mac.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`mac`](../interfaces/ISyncdSnapshot.md#mac)

***

### records

> **records**: [`ISyncdRecord`](../interfaces/ISyncdRecord.md)[]

Defined in: [WAProto/index.d.ts:50446](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50446)

SyncdSnapshot records.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`records`](../interfaces/ISyncdSnapshot.md#records)

***

### version?

> `optional` **version**: `null` \| [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Defined in: [WAProto/index.d.ts:50443](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50443)

SyncdSnapshot version.

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`version`](../interfaces/ISyncdSnapshot.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50522](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50522)

Converts this SyncdSnapshot to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:50459](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50459)

Creates a new SyncdSnapshot instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

Properties to set

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:50485](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50485)

Decodes a SyncdSnapshot message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:50494](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50494)

Decodes a SyncdSnapshot message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50467](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50467)

Encodes the specified SyncdSnapshot message. Does not implicitly [verify](SyncdSnapshot.md#verify) messages.

#### Parameters

##### message

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

SyncdSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50475](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50475)

Encodes the specified SyncdSnapshot message, length delimited. Does not implicitly [verify](SyncdSnapshot.md#verify) messages.

#### Parameters

##### message

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

SyncdSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:50508](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50508)

Creates a SyncdSnapshot message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50529](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50529)

Gets the default type url for SyncdSnapshot

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

Defined in: [WAProto/index.d.ts:50516](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50516)

Creates a plain object from a SyncdSnapshot message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdSnapshot`](SyncdSnapshot.md)

SyncdSnapshot

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50501](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L50501)

Verifies a SyncdSnapshot message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
