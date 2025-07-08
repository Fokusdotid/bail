# Class: PollUpdateMessage

Defined in: [WAProto/index.d.ts:31878](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31878)

Represents a PollUpdateMessage.

## Implements

- [`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

## Constructors

### new PollUpdateMessage()

> **new PollUpdateMessage**(`properties`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:31884](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31884)

Constructs a new PollUpdateMessage.

#### Parameters

##### properties?

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

Properties to set

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

## Properties

### metadata?

> `optional` **metadata**: `null` \| [`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:31893](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31893)

PollUpdateMessage metadata.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`metadata`](../interfaces/IPollUpdateMessage.md#metadata)

***

### pollCreationMessageKey?

> `optional` **pollCreationMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:31887](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31887)

PollUpdateMessage pollCreationMessageKey.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`pollCreationMessageKey`](../interfaces/IPollUpdateMessage.md#pollcreationmessagekey)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:31896](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31896)

PollUpdateMessage senderTimestampMs.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`senderTimestampMs`](../interfaces/IPollUpdateMessage.md#sendertimestampms)

***

### vote?

> `optional` **vote**: `null` \| [`IPollEncValue`](../interfaces/IPollEncValue.md)

Defined in: [WAProto/index.d.ts:31890](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31890)

PollUpdateMessage vote.

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`vote`](../interfaces/IPollUpdateMessage.md#vote)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31966](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31966)

Converts this PollUpdateMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:31903](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31903)

Creates a new PollUpdateMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

Properties to set

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:31929](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31929)

Decodes a PollUpdateMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:31938](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31938)

Decodes a PollUpdateMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31911](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31911)

Encodes the specified PollUpdateMessage message. Does not implicitly [verify](PollUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

PollUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31919](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31919)

Encodes the specified PollUpdateMessage message, length delimited. Does not implicitly [verify](PollUpdateMessage.md#verify) messages.

#### Parameters

##### message

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

PollUpdateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:31952](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31952)

Creates a PollUpdateMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:31973](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31973)

Gets the default type url for PollUpdateMessage

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

Defined in: [WAProto/index.d.ts:31960](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31960)

Creates a plain object from a PollUpdateMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollUpdateMessage`](PollUpdateMessage.md)

PollUpdateMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31945](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L31945)

Verifies a PollUpdateMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
