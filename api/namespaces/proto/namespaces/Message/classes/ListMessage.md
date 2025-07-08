# Class: ListMessage

Defined in: [WAProto/index.d.ts:26730](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26730)

Represents a ListMessage.

## Implements

- [`IListMessage`](../interfaces/IListMessage.md)

## Constructors

### new ListMessage()

> **new ListMessage**(`properties`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:26736](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26736)

Constructs a new ListMessage.

#### Parameters

##### properties?

[`IListMessage`](../interfaces/IListMessage.md)

Properties to set

#### Returns

[`ListMessage`](ListMessage.md)

## Properties

### buttonText?

> `optional` **buttonText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26745](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26745)

ListMessage buttonText.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`buttonText`](../interfaces/IListMessage.md#buttontext)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:26760](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26760)

ListMessage contextInfo.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`contextInfo`](../interfaces/IListMessage.md#contextinfo)

***

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26742](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26742)

ListMessage description.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`description`](../interfaces/IListMessage.md#description)

***

### footerText?

> `optional` **footerText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26757](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26757)

ListMessage footerText.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`footerText`](../interfaces/IListMessage.md#footertext)

***

### listType?

> `optional` **listType**: `null` \| [`ListType`](../namespaces/ListMessage/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:26748](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26748)

ListMessage listType.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`listType`](../interfaces/IListMessage.md#listtype)

***

### productListInfo?

> `optional` **productListInfo**: `null` \| [`IProductListInfo`](../namespaces/ListMessage/interfaces/IProductListInfo.md)

Defined in: [WAProto/index.d.ts:26754](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26754)

ListMessage productListInfo.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`productListInfo`](../interfaces/IListMessage.md#productlistinfo)

***

### sections

> **sections**: [`ISection`](../namespaces/ListMessage/interfaces/ISection.md)[]

Defined in: [WAProto/index.d.ts:26751](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26751)

ListMessage sections.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`sections`](../interfaces/IListMessage.md#sections)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26739](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26739)

ListMessage title.

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`title`](../interfaces/IListMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26830](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26830)

Converts this ListMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:26767](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26767)

Creates a new ListMessage instance using the specified properties.

#### Parameters

##### properties?

[`IListMessage`](../interfaces/IListMessage.md)

Properties to set

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:26793](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26793)

Decodes a ListMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:26802](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26802)

Decodes a ListMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26775](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26775)

Encodes the specified ListMessage message. Does not implicitly [verify](ListMessage.md#verify) messages.

#### Parameters

##### message

[`IListMessage`](../interfaces/IListMessage.md)

ListMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26783](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26783)

Encodes the specified ListMessage message, length delimited. Does not implicitly [verify](ListMessage.md#verify) messages.

#### Parameters

##### message

[`IListMessage`](../interfaces/IListMessage.md)

ListMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:26816](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26816)

Creates a ListMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ListMessage`](ListMessage.md)

ListMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:26837](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26837)

Gets the default type url for ListMessage

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

Defined in: [WAProto/index.d.ts:26824](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26824)

Creates a plain object from a ListMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ListMessage`](ListMessage.md)

ListMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26809](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L26809)

Verifies a ListMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
