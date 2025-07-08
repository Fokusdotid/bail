# Class: LIDMigrationMapping

Defined in: [WAProto/index.d.ts:17151](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17151)

Represents a LIDMigrationMapping.

## Implements

- [`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

## Constructors

### new LIDMigrationMapping()

> **new LIDMigrationMapping**(`properties`?): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:17157](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17157)

Constructs a new LIDMigrationMapping.

#### Parameters

##### properties?

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

Properties to set

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

## Properties

### assignedLid

> **assignedLid**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:17163](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17163)

LIDMigrationMapping assignedLid.

#### Implementation of

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md).[`assignedLid`](../interfaces/ILIDMigrationMapping.md#assignedlid)

***

### latestLid?

> `optional` **latestLid**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:17166](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17166)

LIDMigrationMapping latestLid.

#### Implementation of

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md).[`latestLid`](../interfaces/ILIDMigrationMapping.md#latestlid)

***

### pn

> **pn**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:17160](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17160)

LIDMigrationMapping pn.

#### Implementation of

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md).[`pn`](../interfaces/ILIDMigrationMapping.md#pn)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17236](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17236)

Converts this LIDMigrationMapping to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:17173](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17173)

Creates a new LIDMigrationMapping instance using the specified properties.

#### Parameters

##### properties?

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

Properties to set

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

LIDMigrationMapping instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:17199](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17199)

Decodes a LIDMigrationMapping message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

LIDMigrationMapping

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:17208](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17208)

Decodes a LIDMigrationMapping message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

LIDMigrationMapping

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17181](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17181)

Encodes the specified LIDMigrationMapping message. Does not implicitly [verify](LIDMigrationMapping.md#verify) messages.

#### Parameters

##### message

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

LIDMigrationMapping message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17189](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17189)

Encodes the specified LIDMigrationMapping message, length delimited. Does not implicitly [verify](LIDMigrationMapping.md#verify) messages.

#### Parameters

##### message

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

LIDMigrationMapping message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:17222](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17222)

Creates a LIDMigrationMapping message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

LIDMigrationMapping

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:17243](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17243)

Gets the default type url for LIDMigrationMapping

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

Defined in: [WAProto/index.d.ts:17230](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17230)

Creates a plain object from a LIDMigrationMapping message. Also converts values to other types if specified.

#### Parameters

##### message

[`LIDMigrationMapping`](LIDMigrationMapping.md)

LIDMigrationMapping

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17215](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L17215)

Verifies a LIDMigrationMapping message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
