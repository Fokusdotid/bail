# Class: LIDMigration

Defined in: [WAProto/index.d.ts:12850](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12850)

Represents a LIDMigration.

## Implements

- [`ILIDMigration`](../interfaces/ILIDMigration.md)

## Constructors

### new LIDMigration()

> **new LIDMigration**(`properties`?): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:12856](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12856)

Constructs a new LIDMigration.

#### Parameters

##### properties?

[`ILIDMigration`](../interfaces/ILIDMigration.md)

Properties to set

#### Returns

[`LIDMigration`](LIDMigration.md)

## Properties

### chatDbMigrationTimestamp?

> `optional` **chatDbMigrationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12859](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12859)

LIDMigration chatDbMigrationTimestamp.

#### Implementation of

[`ILIDMigration`](../interfaces/ILIDMigration.md).[`chatDbMigrationTimestamp`](../interfaces/ILIDMigration.md#chatdbmigrationtimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12929](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12929)

Converts this LIDMigration to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:12866](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12866)

Creates a new LIDMigration instance using the specified properties.

#### Parameters

##### properties?

[`ILIDMigration`](../interfaces/ILIDMigration.md)

Properties to set

#### Returns

[`LIDMigration`](LIDMigration.md)

LIDMigration instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:12892](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12892)

Decodes a LIDMigration message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LIDMigration`](LIDMigration.md)

LIDMigration

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:12901](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12901)

Decodes a LIDMigration message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LIDMigration`](LIDMigration.md)

LIDMigration

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12874](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12874)

Encodes the specified LIDMigration message. Does not implicitly [verify](LIDMigration.md#verify) messages.

#### Parameters

##### message

[`ILIDMigration`](../interfaces/ILIDMigration.md)

LIDMigration message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12882](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12882)

Encodes the specified LIDMigration message, length delimited. Does not implicitly [verify](LIDMigration.md#verify) messages.

#### Parameters

##### message

[`ILIDMigration`](../interfaces/ILIDMigration.md)

LIDMigration message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:12915](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12915)

Creates a LIDMigration message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LIDMigration`](LIDMigration.md)

LIDMigration

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12936](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12936)

Gets the default type url for LIDMigration

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

Defined in: [WAProto/index.d.ts:12923](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12923)

Creates a plain object from a LIDMigration message. Also converts values to other types if specified.

#### Parameters

##### message

[`LIDMigration`](LIDMigration.md)

LIDMigration

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12908](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L12908)

Verifies a LIDMigration message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
