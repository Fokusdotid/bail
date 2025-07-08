# Class: CommentMessage

Defined in: [WAProto/index.d.ts:21694](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21694)

Represents a CommentMessage.

## Implements

- [`ICommentMessage`](../interfaces/ICommentMessage.md)

## Constructors

### new CommentMessage()

> **new CommentMessage**(`properties`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:21700](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21700)

Constructs a new CommentMessage.

#### Parameters

##### properties?

[`ICommentMessage`](../interfaces/ICommentMessage.md)

Properties to set

#### Returns

[`CommentMessage`](CommentMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:21703](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21703)

CommentMessage message.

#### Implementation of

[`ICommentMessage`](../interfaces/ICommentMessage.md).[`message`](../interfaces/ICommentMessage.md#message)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:21706](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21706)

CommentMessage targetMessageKey.

#### Implementation of

[`ICommentMessage`](../interfaces/ICommentMessage.md).[`targetMessageKey`](../interfaces/ICommentMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21776](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21776)

Converts this CommentMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:21713](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21713)

Creates a new CommentMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICommentMessage`](../interfaces/ICommentMessage.md)

Properties to set

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:21739](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21739)

Decodes a CommentMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:21748](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21748)

Decodes a CommentMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21721](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21721)

Encodes the specified CommentMessage message. Does not implicitly [verify](CommentMessage.md#verify) messages.

#### Parameters

##### message

[`ICommentMessage`](../interfaces/ICommentMessage.md)

CommentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21729](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21729)

Encodes the specified CommentMessage message, length delimited. Does not implicitly [verify](CommentMessage.md#verify) messages.

#### Parameters

##### message

[`ICommentMessage`](../interfaces/ICommentMessage.md)

CommentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:21762](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21762)

Creates a CommentMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CommentMessage`](CommentMessage.md)

CommentMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21783](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21783)

Gets the default type url for CommentMessage

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

Defined in: [WAProto/index.d.ts:21770](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21770)

Creates a plain object from a CommentMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CommentMessage`](CommentMessage.md)

CommentMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21755](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L21755)

Verifies a CommentMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
