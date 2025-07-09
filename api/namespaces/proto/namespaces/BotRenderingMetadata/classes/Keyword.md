# Class: Keyword

Defined in: [WAProto/index.d.ts:6933](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6933)

Represents a Keyword.

## Implements

- [`IKeyword`](../interfaces/IKeyword.md)

## Constructors

### new Keyword()

> **new Keyword**(`properties`?): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:6939](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6939)

Constructs a new Keyword.

#### Parameters

##### properties?

[`IKeyword`](../interfaces/IKeyword.md)

Properties to set

#### Returns

[`Keyword`](Keyword.md)

## Properties

### associatedPrompts

> **associatedPrompts**: `string`[]

Defined in: [WAProto/index.d.ts:6945](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6945)

Keyword associatedPrompts.

#### Implementation of

[`IKeyword`](../interfaces/IKeyword.md).[`associatedPrompts`](../interfaces/IKeyword.md#associatedprompts)

***

### value?

> `optional` **value**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6942](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6942)

Keyword value.

#### Implementation of

[`IKeyword`](../interfaces/IKeyword.md).[`value`](../interfaces/IKeyword.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7015](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7015)

Converts this Keyword to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:6952](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6952)

Creates a new Keyword instance using the specified properties.

#### Parameters

##### properties?

[`IKeyword`](../interfaces/IKeyword.md)

Properties to set

#### Returns

[`Keyword`](Keyword.md)

Keyword instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:6978](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6978)

Decodes a Keyword message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Keyword`](Keyword.md)

Keyword

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:6987](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6987)

Decodes a Keyword message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Keyword`](Keyword.md)

Keyword

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6960](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6960)

Encodes the specified Keyword message. Does not implicitly [verify](Keyword.md#verify) messages.

#### Parameters

##### message

[`IKeyword`](../interfaces/IKeyword.md)

Keyword message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6968](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6968)

Encodes the specified Keyword message, length delimited. Does not implicitly [verify](Keyword.md#verify) messages.

#### Parameters

##### message

[`IKeyword`](../interfaces/IKeyword.md)

Keyword message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:7001](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7001)

Creates a Keyword message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Keyword`](Keyword.md)

Keyword

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7022](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7022)

Gets the default type url for Keyword

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

Defined in: [WAProto/index.d.ts:7009](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L7009)

Creates a plain object from a Keyword message. Also converts values to other types if specified.

#### Parameters

##### message

[`Keyword`](Keyword.md)

Keyword

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6994](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L6994)

Verifies a Keyword message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
