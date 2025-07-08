# Class: SyncdMutation

Defined in: [WAProto/index.d.ts:49965](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L49965)

Represents a SyncdMutation.

## Implements

- [`ISyncdMutation`](../interfaces/ISyncdMutation.md)

## Constructors

### new SyncdMutation()

> **new SyncdMutation**(`properties`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:49971](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L49971)

Constructs a new SyncdMutation.

#### Parameters

##### properties?

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

Properties to set

#### Returns

[`SyncdMutation`](SyncdMutation.md)

## Properties

### operation?

> `optional` **operation**: `null` \| [`SyncdOperation`](../namespaces/SyncdMutation/enumerations/SyncdOperation.md)

Defined in: [WAProto/index.d.ts:49974](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L49974)

SyncdMutation operation.

#### Implementation of

[`ISyncdMutation`](../interfaces/ISyncdMutation.md).[`operation`](../interfaces/ISyncdMutation.md#operation)

***

### record?

> `optional` **record**: `null` \| [`ISyncdRecord`](../interfaces/ISyncdRecord.md)

Defined in: [WAProto/index.d.ts:49977](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L49977)

SyncdMutation record.

#### Implementation of

[`ISyncdMutation`](../interfaces/ISyncdMutation.md).[`record`](../interfaces/ISyncdMutation.md#record)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50047](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50047)

Converts this SyncdMutation to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:49984](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L49984)

Creates a new SyncdMutation instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

Properties to set

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:50010](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50010)

Decodes a SyncdMutation message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:50019](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50019)

Decodes a SyncdMutation message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49992](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L49992)

Encodes the specified SyncdMutation message. Does not implicitly [verify](SyncdMutation.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

SyncdMutation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50000](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50000)

Encodes the specified SyncdMutation message, length delimited. Does not implicitly [verify](SyncdMutation.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

SyncdMutation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:50033](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50033)

Creates a SyncdMutation message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50054](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50054)

Gets the default type url for SyncdMutation

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

Defined in: [WAProto/index.d.ts:50041](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50041)

Creates a plain object from a SyncdMutation message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdMutation`](SyncdMutation.md)

SyncdMutation

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50026](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L50026)

Verifies a SyncdMutation message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
