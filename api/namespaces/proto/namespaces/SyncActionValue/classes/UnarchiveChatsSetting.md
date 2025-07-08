# Class: UnarchiveChatsSetting

Defined in: [WAProto/index.d.ts:49362](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49362)

Represents an UnarchiveChatsSetting.

## Implements

- [`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

## Constructors

### new UnarchiveChatsSetting()

> **new UnarchiveChatsSetting**(`properties`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:49368](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49368)

Constructs a new UnarchiveChatsSetting.

#### Parameters

##### properties?

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

Properties to set

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

## Properties

### unarchiveChats?

> `optional` **unarchiveChats**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:49371](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49371)

UnarchiveChatsSetting unarchiveChats.

#### Implementation of

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md).[`unarchiveChats`](../interfaces/IUnarchiveChatsSetting.md#unarchivechats)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:49441](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49441)

Converts this UnarchiveChatsSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:49378](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49378)

Creates a new UnarchiveChatsSetting instance using the specified properties.

#### Parameters

##### properties?

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

Properties to set

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:49404](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49404)

Decodes an UnarchiveChatsSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:49413](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49413)

Decodes an UnarchiveChatsSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49386](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49386)

Encodes the specified UnarchiveChatsSetting message. Does not implicitly [verify](UnarchiveChatsSetting.md#verify) messages.

#### Parameters

##### message

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

UnarchiveChatsSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49394](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49394)

Encodes the specified UnarchiveChatsSetting message, length delimited. Does not implicitly [verify](UnarchiveChatsSetting.md#verify) messages.

#### Parameters

##### message

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

UnarchiveChatsSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:49427](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49427)

Creates an UnarchiveChatsSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:49448](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49448)

Gets the default type url for UnarchiveChatsSetting

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

Defined in: [WAProto/index.d.ts:49435](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49435)

Creates a plain object from an UnarchiveChatsSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

UnarchiveChatsSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:49420](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L49420)

Verifies an UnarchiveChatsSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
