# Class: QuickReplyAction

Defined in: [WAProto/index.d.ts:48177](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48177)

Represents a QuickReplyAction.

## Implements

- [`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

## Constructors

### new QuickReplyAction()

> **new QuickReplyAction**(`properties`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:48183](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48183)

Constructs a new QuickReplyAction.

#### Parameters

##### properties?

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

Properties to set

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

## Properties

### count?

> `optional` **count**: `null` \| `number`

Defined in: [WAProto/index.d.ts:48195](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48195)

QuickReplyAction count.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`count`](../interfaces/IQuickReplyAction.md#count)

***

### deleted?

> `optional` **deleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:48198](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48198)

QuickReplyAction deleted.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`deleted`](../interfaces/IQuickReplyAction.md#deleted)

***

### keywords

> **keywords**: `string`[]

Defined in: [WAProto/index.d.ts:48192](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48192)

QuickReplyAction keywords.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`keywords`](../interfaces/IQuickReplyAction.md#keywords)

***

### message?

> `optional` **message**: `null` \| `string`

Defined in: [WAProto/index.d.ts:48189](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48189)

QuickReplyAction message.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`message`](../interfaces/IQuickReplyAction.md#message)

***

### shortcut?

> `optional` **shortcut**: `null` \| `string`

Defined in: [WAProto/index.d.ts:48186](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48186)

QuickReplyAction shortcut.

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`shortcut`](../interfaces/IQuickReplyAction.md#shortcut)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48268](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48268)

Converts this QuickReplyAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:48205](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48205)

Creates a new QuickReplyAction instance using the specified properties.

#### Parameters

##### properties?

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

Properties to set

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:48231](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48231)

Decodes a QuickReplyAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:48240](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48240)

Decodes a QuickReplyAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48213](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48213)

Encodes the specified QuickReplyAction message. Does not implicitly [verify](QuickReplyAction.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

QuickReplyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48221](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48221)

Encodes the specified QuickReplyAction message, length delimited. Does not implicitly [verify](QuickReplyAction.md#verify) messages.

#### Parameters

##### message

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

QuickReplyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:48254](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48254)

Creates a QuickReplyAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48275](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48275)

Gets the default type url for QuickReplyAction

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

Defined in: [WAProto/index.d.ts:48262](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48262)

Creates a plain object from a QuickReplyAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`QuickReplyAction`](QuickReplyAction.md)

QuickReplyAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48247](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48247)

Verifies a QuickReplyAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
