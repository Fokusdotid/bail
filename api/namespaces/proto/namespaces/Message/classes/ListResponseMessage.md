# Class: ListResponseMessage

Defined in: [WAProto/index.d.ts:27494](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27494)

Represents a ListResponseMessage.

## Implements

- [`IListResponseMessage`](../interfaces/IListResponseMessage.md)

## Constructors

### new ListResponseMessage()

> **new ListResponseMessage**(`properties`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:27500](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27500)

Constructs a new ListResponseMessage.

#### Parameters

##### properties?

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

Properties to set

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:27512](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27512)

ListResponseMessage contextInfo.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`contextInfo`](../interfaces/IListResponseMessage.md#contextinfo)

***

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27515](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27515)

ListResponseMessage description.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`description`](../interfaces/IListResponseMessage.md#description)

***

### listType?

> `optional` **listType**: `null` \| [`ListType`](../namespaces/ListResponseMessage/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:27506](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27506)

ListResponseMessage listType.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`listType`](../interfaces/IListResponseMessage.md#listtype)

***

### singleSelectReply?

> `optional` **singleSelectReply**: `null` \| [`ISingleSelectReply`](../namespaces/ListResponseMessage/interfaces/ISingleSelectReply.md)

Defined in: [WAProto/index.d.ts:27509](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27509)

ListResponseMessage singleSelectReply.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`singleSelectReply`](../interfaces/IListResponseMessage.md#singleselectreply)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27503](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27503)

ListResponseMessage title.

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`title`](../interfaces/IListResponseMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27585](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27585)

Converts this ListResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:27522](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27522)

Creates a new ListResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

Properties to set

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:27548](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27548)

Decodes a ListResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:27557](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27557)

Decodes a ListResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27530](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27530)

Encodes the specified ListResponseMessage message. Does not implicitly [verify](ListResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

ListResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27538](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27538)

Encodes the specified ListResponseMessage message, length delimited. Does not implicitly [verify](ListResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

ListResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:27571](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27571)

Creates a ListResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:27592](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27592)

Gets the default type url for ListResponseMessage

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

Defined in: [WAProto/index.d.ts:27579](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27579)

Creates a plain object from a ListResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ListResponseMessage`](ListResponseMessage.md)

ListResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27564](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L27564)

Verifies a ListResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
