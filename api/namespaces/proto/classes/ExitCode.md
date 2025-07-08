# Class: ExitCode

Defined in: [WAProto/index.d.ts:14562](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14562)

Represents an ExitCode.

## Implements

- [`IExitCode`](../interfaces/IExitCode.md)

## Constructors

### new ExitCode()

> **new ExitCode**(`properties`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:14568](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14568)

Constructs a new ExitCode.

#### Parameters

##### properties?

[`IExitCode`](../interfaces/IExitCode.md)

Properties to set

#### Returns

[`ExitCode`](ExitCode.md)

## Properties

### code?

> `optional` **code**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:14571](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14571)

ExitCode code.

#### Implementation of

[`IExitCode`](../interfaces/IExitCode.md).[`code`](../interfaces/IExitCode.md#code)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:14574](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14574)

ExitCode text.

#### Implementation of

[`IExitCode`](../interfaces/IExitCode.md).[`text`](../interfaces/IExitCode.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14644](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14644)

Converts this ExitCode to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:14581](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14581)

Creates a new ExitCode instance using the specified properties.

#### Parameters

##### properties?

[`IExitCode`](../interfaces/IExitCode.md)

Properties to set

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:14607](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14607)

Decodes an ExitCode message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:14616](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14616)

Decodes an ExitCode message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14589](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14589)

Encodes the specified ExitCode message. Does not implicitly [verify](ExitCode.md#verify) messages.

#### Parameters

##### message

[`IExitCode`](../interfaces/IExitCode.md)

ExitCode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14597](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14597)

Encodes the specified ExitCode message, length delimited. Does not implicitly [verify](ExitCode.md#verify) messages.

#### Parameters

##### message

[`IExitCode`](../interfaces/IExitCode.md)

ExitCode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:14630](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14630)

Creates an ExitCode message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ExitCode`](ExitCode.md)

ExitCode

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:14651](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14651)

Gets the default type url for ExitCode

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

Defined in: [WAProto/index.d.ts:14638](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14638)

Creates a plain object from an ExitCode message. Also converts values to other types if specified.

#### Parameters

##### message

[`ExitCode`](ExitCode.md)

ExitCode

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14623](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L14623)

Verifies an ExitCode message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
