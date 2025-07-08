# Class: CommentMetadata

Defined in: [WAProto/index.d.ts:10336](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10336)

Represents a CommentMetadata.

## Implements

- [`ICommentMetadata`](../interfaces/ICommentMetadata.md)

## Constructors

### new CommentMetadata()

> **new CommentMetadata**(`properties`?): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:10342](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10342)

Constructs a new CommentMetadata.

#### Parameters

##### properties?

[`ICommentMetadata`](../interfaces/ICommentMetadata.md)

Properties to set

#### Returns

[`CommentMetadata`](CommentMetadata.md)

## Properties

### commentParentKey?

> `optional` **commentParentKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:10345](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10345)

CommentMetadata commentParentKey.

#### Implementation of

[`ICommentMetadata`](../interfaces/ICommentMetadata.md).[`commentParentKey`](../interfaces/ICommentMetadata.md#commentparentkey)

***

### replyCount?

> `optional` **replyCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10348](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10348)

CommentMetadata replyCount.

#### Implementation of

[`ICommentMetadata`](../interfaces/ICommentMetadata.md).[`replyCount`](../interfaces/ICommentMetadata.md#replycount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10418](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10418)

Converts this CommentMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:10355](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10355)

Creates a new CommentMetadata instance using the specified properties.

#### Parameters

##### properties?

[`ICommentMetadata`](../interfaces/ICommentMetadata.md)

Properties to set

#### Returns

[`CommentMetadata`](CommentMetadata.md)

CommentMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:10381](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10381)

Decodes a CommentMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CommentMetadata`](CommentMetadata.md)

CommentMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:10390](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10390)

Decodes a CommentMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CommentMetadata`](CommentMetadata.md)

CommentMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10363](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10363)

Encodes the specified CommentMetadata message. Does not implicitly [verify](CommentMetadata.md#verify) messages.

#### Parameters

##### message

[`ICommentMetadata`](../interfaces/ICommentMetadata.md)

CommentMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10371](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10371)

Encodes the specified CommentMetadata message, length delimited. Does not implicitly [verify](CommentMetadata.md#verify) messages.

#### Parameters

##### message

[`ICommentMetadata`](../interfaces/ICommentMetadata.md)

CommentMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:10404](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10404)

Creates a CommentMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CommentMetadata`](CommentMetadata.md)

CommentMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10425](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10425)

Gets the default type url for CommentMetadata

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

Defined in: [WAProto/index.d.ts:10412](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10412)

Creates a plain object from a CommentMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`CommentMetadata`](CommentMetadata.md)

CommentMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10397](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L10397)

Verifies a CommentMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
