# Class: SyncdMutations

Defined in: [WAProto/index.d.ts:50074](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50074)

Represents a SyncdMutations.

## Implements

- [`ISyncdMutations`](../interfaces/ISyncdMutations.md)

## Constructors

### new SyncdMutations()

> **new SyncdMutations**(`properties`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:50080](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50080)

Constructs a new SyncdMutations.

#### Parameters

##### properties?

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

Properties to set

#### Returns

[`SyncdMutations`](SyncdMutations.md)

## Properties

### mutations

> **mutations**: [`ISyncdMutation`](../interfaces/ISyncdMutation.md)[]

Defined in: [WAProto/index.d.ts:50083](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50083)

SyncdMutations mutations.

#### Implementation of

[`ISyncdMutations`](../interfaces/ISyncdMutations.md).[`mutations`](../interfaces/ISyncdMutations.md#mutations)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50153](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50153)

Converts this SyncdMutations to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:50090](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50090)

Creates a new SyncdMutations instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

Properties to set

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:50116](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50116)

Decodes a SyncdMutations message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:50125](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50125)

Decodes a SyncdMutations message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50098](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50098)

Encodes the specified SyncdMutations message. Does not implicitly [verify](SyncdMutations.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

SyncdMutations message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50106](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50106)

Encodes the specified SyncdMutations message, length delimited. Does not implicitly [verify](SyncdMutations.md#verify) messages.

#### Parameters

##### message

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

SyncdMutations message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:50139](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50139)

Creates a SyncdMutations message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50160](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50160)

Gets the default type url for SyncdMutations

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

Defined in: [WAProto/index.d.ts:50147](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50147)

Creates a plain object from a SyncdMutations message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdMutations`](SyncdMutations.md)

SyncdMutations

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50132](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L50132)

Verifies a SyncdMutations message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
