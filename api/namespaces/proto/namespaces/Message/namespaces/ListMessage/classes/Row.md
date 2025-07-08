# Class: Row

Defined in: [WAProto/index.d.ts:27275](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27275)

Represents a Row.

## Implements

- [`IRow`](../interfaces/IRow.md)

## Constructors

### new Row()

> **new Row**(`properties`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:27281](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27281)

Constructs a new Row.

#### Parameters

##### properties?

[`IRow`](../interfaces/IRow.md)

Properties to set

#### Returns

[`Row`](Row.md)

## Properties

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27287](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27287)

Row description.

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`description`](../interfaces/IRow.md#description)

***

### rowId?

> `optional` **rowId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27290](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27290)

Row rowId.

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`rowId`](../interfaces/IRow.md#rowid)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27284](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27284)

Row title.

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`title`](../interfaces/IRow.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27360](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27360)

Converts this Row to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:27297](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27297)

Creates a new Row instance using the specified properties.

#### Parameters

##### properties?

[`IRow`](../interfaces/IRow.md)

Properties to set

#### Returns

[`Row`](Row.md)

Row instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:27323](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27323)

Decodes a Row message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Row`](Row.md)

Row

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:27332](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27332)

Decodes a Row message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Row`](Row.md)

Row

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27305](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27305)

Encodes the specified Row message. Does not implicitly [verify](Row.md#verify) messages.

#### Parameters

##### message

[`IRow`](../interfaces/IRow.md)

Row message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27313](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27313)

Encodes the specified Row message, length delimited. Does not implicitly [verify](Row.md#verify) messages.

#### Parameters

##### message

[`IRow`](../interfaces/IRow.md)

Row message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:27346](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27346)

Creates a Row message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Row`](Row.md)

Row

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:27367](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27367)

Gets the default type url for Row

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

Defined in: [WAProto/index.d.ts:27354](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27354)

Creates a plain object from a Row message. Also converts values to other types if specified.

#### Parameters

##### message

[`Row`](Row.md)

Row

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27339](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27339)

Verifies a Row message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
