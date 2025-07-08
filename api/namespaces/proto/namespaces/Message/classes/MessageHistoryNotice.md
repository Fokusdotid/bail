# Class: MessageHistoryNotice

Defined in: [WAProto/index.d.ts:28407](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28407)

Represents a MessageHistoryNotice.

## Implements

- [`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

## Constructors

### new MessageHistoryNotice()

> **new MessageHistoryNotice**(`properties`?): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:28413](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28413)

Constructs a new MessageHistoryNotice.

#### Parameters

##### properties?

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

Properties to set

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:28416](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28416)

MessageHistoryNotice contextInfo.

#### Implementation of

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md).[`contextInfo`](../interfaces/IMessageHistoryNotice.md#contextinfo)

***

### messageHistoryMetadata?

> `optional` **messageHistoryMetadata**: `null` \| [`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:28419](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28419)

MessageHistoryNotice messageHistoryMetadata.

#### Implementation of

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md).[`messageHistoryMetadata`](../interfaces/IMessageHistoryNotice.md#messagehistorymetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28489](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28489)

Converts this MessageHistoryNotice to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:28426](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28426)

Creates a new MessageHistoryNotice instance using the specified properties.

#### Parameters

##### properties?

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

Properties to set

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

MessageHistoryNotice instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:28452](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28452)

Decodes a MessageHistoryNotice message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

MessageHistoryNotice

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:28461](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28461)

Decodes a MessageHistoryNotice message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

MessageHistoryNotice

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28434](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28434)

Encodes the specified MessageHistoryNotice message. Does not implicitly [verify](MessageHistoryNotice.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

MessageHistoryNotice message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28442](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28442)

Encodes the specified MessageHistoryNotice message, length delimited. Does not implicitly [verify](MessageHistoryNotice.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

MessageHistoryNotice message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:28475](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28475)

Creates a MessageHistoryNotice message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

MessageHistoryNotice

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:28496](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28496)

Gets the default type url for MessageHistoryNotice

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

Defined in: [WAProto/index.d.ts:28483](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28483)

Creates a plain object from a MessageHistoryNotice message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageHistoryNotice`](MessageHistoryNotice.md)

MessageHistoryNotice

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28468](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28468)

Verifies a MessageHistoryNotice message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
