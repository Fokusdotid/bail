# Class: SenderKeyRecordStructure

Defined in: [WAProto/index.d.ts:41165](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41165)

Represents a SenderKeyRecordStructure.

## Implements

- [`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

## Constructors

### new SenderKeyRecordStructure()

> **new SenderKeyRecordStructure**(`properties`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:41171](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41171)

Constructs a new SenderKeyRecordStructure.

#### Parameters

##### properties?

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

Properties to set

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

## Properties

### senderKeyStates

> **senderKeyStates**: [`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)[]

Defined in: [WAProto/index.d.ts:41174](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41174)

SenderKeyRecordStructure senderKeyStates.

#### Implementation of

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md).[`senderKeyStates`](../interfaces/ISenderKeyRecordStructure.md#senderkeystates)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:41244](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41244)

Converts this SenderKeyRecordStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:41181](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41181)

Creates a new SenderKeyRecordStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

Properties to set

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:41207](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41207)

Decodes a SenderKeyRecordStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:41216](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41216)

Decodes a SenderKeyRecordStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41189](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41189)

Encodes the specified SenderKeyRecordStructure message. Does not implicitly [verify](SenderKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

SenderKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41197](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41197)

Encodes the specified SenderKeyRecordStructure message, length delimited. Does not implicitly [verify](SenderKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

SenderKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:41230](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41230)

Creates a SenderKeyRecordStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:41251](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41251)

Gets the default type url for SenderKeyRecordStructure

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

Defined in: [WAProto/index.d.ts:41238](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41238)

Creates a plain object from a SenderKeyRecordStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

SenderKeyRecordStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:41223](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L41223)

Verifies a SenderKeyRecordStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
