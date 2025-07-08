# Class: Value

Defined in: [WAProto/index.d.ts:51720](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51720)

Represents a Value.

## Implements

- [`IValue`](../interfaces/IValue.md)

## Constructors

### new Value()

> **new Value**(`properties`?): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:51726](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51726)

Constructs a new Value.

#### Parameters

##### properties?

[`IValue`](../interfaces/IValue.md)

Properties to set

#### Returns

[`Value`](Value.md)

## Properties

### asBlob?

> `optional` **asBlob**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:51729](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51729)

Value asBlob.

#### Implementation of

[`IValue`](../interfaces/IValue.md).[`asBlob`](../interfaces/IValue.md#asblob)

***

### asUnsignedInteger?

> `optional` **asUnsignedInteger**: `null` \| `number`

Defined in: [WAProto/index.d.ts:51732](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51732)

Value asUnsignedInteger.

#### Implementation of

[`IValue`](../interfaces/IValue.md).[`asUnsignedInteger`](../interfaces/IValue.md#asunsignedinteger)

***

### value?

> `optional` **value**: `"asBlob"` \| `"asUnsignedInteger"`

Defined in: [WAProto/index.d.ts:51735](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51735)

Value value.

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51805](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51805)

Converts this Value to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:51742](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51742)

Creates a new Value instance using the specified properties.

#### Parameters

##### properties?

[`IValue`](../interfaces/IValue.md)

Properties to set

#### Returns

[`Value`](Value.md)

Value instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:51768](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51768)

Decodes a Value message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Value`](Value.md)

Value

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:51777](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51777)

Decodes a Value message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Value`](Value.md)

Value

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51750](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51750)

Encodes the specified Value message. Does not implicitly [verify](Value.md#verify) messages.

#### Parameters

##### message

[`IValue`](../interfaces/IValue.md)

Value message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51758](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51758)

Encodes the specified Value message, length delimited. Does not implicitly [verify](Value.md#verify) messages.

#### Parameters

##### message

[`IValue`](../interfaces/IValue.md)

Value message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:51791](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51791)

Creates a Value message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Value`](Value.md)

Value

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51812](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51812)

Gets the default type url for Value

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

Defined in: [WAProto/index.d.ts:51799](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51799)

Creates a plain object from a Value message. Also converts values to other types if specified.

#### Parameters

##### message

[`Value`](Value.md)

Value

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51784](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L51784)

Verifies a Value message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
