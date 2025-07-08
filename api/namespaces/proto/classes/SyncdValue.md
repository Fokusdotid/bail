# Class: SyncdValue

Defined in: [WAProto/index.d.ts:50540](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50540)

Represents a SyncdValue.

## Implements

- [`ISyncdValue`](../interfaces/ISyncdValue.md)

## Constructors

### new SyncdValue()

> **new SyncdValue**(`properties`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:50546](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50546)

Constructs a new SyncdValue.

#### Parameters

##### properties?

[`ISyncdValue`](../interfaces/ISyncdValue.md)

Properties to set

#### Returns

[`SyncdValue`](SyncdValue.md)

## Properties

### blob?

> `optional` **blob**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:50549](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50549)

SyncdValue blob.

#### Implementation of

[`ISyncdValue`](../interfaces/ISyncdValue.md).[`blob`](../interfaces/ISyncdValue.md#blob)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50619](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50619)

Converts this SyncdValue to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:50556](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50556)

Creates a new SyncdValue instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdValue`](../interfaces/ISyncdValue.md)

Properties to set

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:50582](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50582)

Decodes a SyncdValue message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:50591](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50591)

Decodes a SyncdValue message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50564](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50564)

Encodes the specified SyncdValue message. Does not implicitly [verify](SyncdValue.md#verify) messages.

#### Parameters

##### message

[`ISyncdValue`](../interfaces/ISyncdValue.md)

SyncdValue message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50572](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50572)

Encodes the specified SyncdValue message, length delimited. Does not implicitly [verify](SyncdValue.md#verify) messages.

#### Parameters

##### message

[`ISyncdValue`](../interfaces/ISyncdValue.md)

SyncdValue message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:50605](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50605)

Creates a SyncdValue message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdValue`](SyncdValue.md)

SyncdValue

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50626](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50626)

Gets the default type url for SyncdValue

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

Defined in: [WAProto/index.d.ts:50613](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50613)

Creates a plain object from a SyncdValue message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdValue`](SyncdValue.md)

SyncdValue

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50598](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L50598)

Verifies a SyncdValue message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
