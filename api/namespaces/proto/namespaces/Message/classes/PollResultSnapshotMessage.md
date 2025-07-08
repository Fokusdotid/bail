# Class: PollResultSnapshotMessage

Defined in: [WAProto/index.d.ts:31660](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31660)

Represents a PollResultSnapshotMessage.

## Implements

- [`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

## Constructors

### new PollResultSnapshotMessage()

> **new PollResultSnapshotMessage**(`properties`?): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:31666](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31666)

Constructs a new PollResultSnapshotMessage.

#### Parameters

##### properties?

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

Properties to set

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:31675](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31675)

PollResultSnapshotMessage contextInfo.

#### Implementation of

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md).[`contextInfo`](../interfaces/IPollResultSnapshotMessage.md#contextinfo)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:31669](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31669)

PollResultSnapshotMessage name.

#### Implementation of

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md).[`name`](../interfaces/IPollResultSnapshotMessage.md#name)

***

### pollVotes

> **pollVotes**: [`IPollVote`](../namespaces/PollResultSnapshotMessage/interfaces/IPollVote.md)[]

Defined in: [WAProto/index.d.ts:31672](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31672)

PollResultSnapshotMessage pollVotes.

#### Implementation of

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md).[`pollVotes`](../interfaces/IPollResultSnapshotMessage.md#pollvotes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31745](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31745)

Converts this PollResultSnapshotMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:31682](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31682)

Creates a new PollResultSnapshotMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

Properties to set

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

PollResultSnapshotMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:31708](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31708)

Decodes a PollResultSnapshotMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

PollResultSnapshotMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:31717](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31717)

Decodes a PollResultSnapshotMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

PollResultSnapshotMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31690](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31690)

Encodes the specified PollResultSnapshotMessage message. Does not implicitly [verify](PollResultSnapshotMessage.md#verify) messages.

#### Parameters

##### message

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

PollResultSnapshotMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31698](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31698)

Encodes the specified PollResultSnapshotMessage message, length delimited. Does not implicitly [verify](PollResultSnapshotMessage.md#verify) messages.

#### Parameters

##### message

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

PollResultSnapshotMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:31731](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31731)

Creates a PollResultSnapshotMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

PollResultSnapshotMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:31752](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31752)

Gets the default type url for PollResultSnapshotMessage

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

Defined in: [WAProto/index.d.ts:31739](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31739)

Creates a plain object from a PollResultSnapshotMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

PollResultSnapshotMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31724](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L31724)

Verifies a PollResultSnapshotMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
