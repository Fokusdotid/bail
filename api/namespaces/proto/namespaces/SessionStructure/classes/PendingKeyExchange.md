# Class: PendingKeyExchange

Defined in: [WAProto/index.d.ts:42311](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42311)

Represents a PendingKeyExchange.

## Implements

- [`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

## Constructors

### new PendingKeyExchange()

> **new PendingKeyExchange**(`properties`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:42317](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42317)

Constructs a new PendingKeyExchange.

#### Parameters

##### properties?

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

Properties to set

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

## Properties

### localBaseKey?

> `optional` **localBaseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42323](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42323)

PendingKeyExchange localBaseKey.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localBaseKey`](../interfaces/IPendingKeyExchange.md#localbasekey)

***

### localBaseKeyPrivate?

> `optional` **localBaseKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42326](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42326)

PendingKeyExchange localBaseKeyPrivate.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localBaseKeyPrivate`](../interfaces/IPendingKeyExchange.md#localbasekeyprivate)

***

### localIdentityKey?

> `optional` **localIdentityKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42335](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42335)

PendingKeyExchange localIdentityKey.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localIdentityKey`](../interfaces/IPendingKeyExchange.md#localidentitykey)

***

### localIdentityKeyPrivate?

> `optional` **localIdentityKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42338](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42338)

PendingKeyExchange localIdentityKeyPrivate.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localIdentityKeyPrivate`](../interfaces/IPendingKeyExchange.md#localidentitykeyprivate)

***

### localRatchetKey?

> `optional` **localRatchetKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42329](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42329)

PendingKeyExchange localRatchetKey.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localRatchetKey`](../interfaces/IPendingKeyExchange.md#localratchetkey)

***

### localRatchetKeyPrivate?

> `optional` **localRatchetKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42332](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42332)

PendingKeyExchange localRatchetKeyPrivate.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localRatchetKeyPrivate`](../interfaces/IPendingKeyExchange.md#localratchetkeyprivate)

***

### sequence?

> `optional` **sequence**: `null` \| `number`

Defined in: [WAProto/index.d.ts:42320](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42320)

PendingKeyExchange sequence.

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`sequence`](../interfaces/IPendingKeyExchange.md#sequence)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:42408](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42408)

Converts this PendingKeyExchange to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:42345](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42345)

Creates a new PendingKeyExchange instance using the specified properties.

#### Parameters

##### properties?

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

Properties to set

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:42371](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42371)

Decodes a PendingKeyExchange message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:42380](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42380)

Decodes a PendingKeyExchange message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42353](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42353)

Encodes the specified PendingKeyExchange message. Does not implicitly [verify](PendingKeyExchange.md#verify) messages.

#### Parameters

##### message

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

PendingKeyExchange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42361](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42361)

Encodes the specified PendingKeyExchange message, length delimited. Does not implicitly [verify](PendingKeyExchange.md#verify) messages.

#### Parameters

##### message

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

PendingKeyExchange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:42394](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42394)

Creates a PendingKeyExchange message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:42415](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42415)

Gets the default type url for PendingKeyExchange

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

Defined in: [WAProto/index.d.ts:42402](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42402)

Creates a plain object from a PendingKeyExchange message. Also converts values to other types if specified.

#### Parameters

##### message

[`PendingKeyExchange`](PendingKeyExchange.md)

PendingKeyExchange

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:42387](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L42387)

Verifies a PendingKeyExchange message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
