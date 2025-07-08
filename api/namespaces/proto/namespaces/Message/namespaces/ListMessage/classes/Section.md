# Class: Section

Defined in: [WAProto/index.d.ts:27381](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27381)

Represents a Section.

## Implements

- [`ISection`](../interfaces/ISection.md)

## Constructors

### new Section()

> **new Section**(`properties`?): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:27387](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27387)

Constructs a new Section.

#### Parameters

##### properties?

[`ISection`](../interfaces/ISection.md)

Properties to set

#### Returns

[`Section`](Section.md)

## Properties

### rows

> **rows**: [`IRow`](../interfaces/IRow.md)[]

Defined in: [WAProto/index.d.ts:27393](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27393)

Section rows.

#### Implementation of

[`ISection`](../interfaces/ISection.md).[`rows`](../interfaces/ISection.md#rows)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27390](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27390)

Section title.

#### Implementation of

[`ISection`](../interfaces/ISection.md).[`title`](../interfaces/ISection.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27463](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27463)

Converts this Section to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:27400](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27400)

Creates a new Section instance using the specified properties.

#### Parameters

##### properties?

[`ISection`](../interfaces/ISection.md)

Properties to set

#### Returns

[`Section`](Section.md)

Section instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:27426](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27426)

Decodes a Section message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Section`](Section.md)

Section

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:27435](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27435)

Decodes a Section message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Section`](Section.md)

Section

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27408](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27408)

Encodes the specified Section message. Does not implicitly [verify](Section.md#verify) messages.

#### Parameters

##### message

[`ISection`](../interfaces/ISection.md)

Section message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27416](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27416)

Encodes the specified Section message, length delimited. Does not implicitly [verify](Section.md#verify) messages.

#### Parameters

##### message

[`ISection`](../interfaces/ISection.md)

Section message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:27449](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27449)

Creates a Section message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Section`](Section.md)

Section

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:27470](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27470)

Gets the default type url for Section

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

Defined in: [WAProto/index.d.ts:27457](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27457)

Creates a plain object from a Section message. Also converts values to other types if specified.

#### Parameters

##### message

[`Section`](Section.md)

Section

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27442](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L27442)

Verifies a Section message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
