# Class: MessageHistoryMetadata

Defined in: [WAProto/index.d.ts:28301](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28301)

Represents a MessageHistoryMetadata.

## Implements

- [`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

## Constructors

### new MessageHistoryMetadata()

> **new MessageHistoryMetadata**(`properties`?): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:28307](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28307)

Constructs a new MessageHistoryMetadata.

#### Parameters

##### properties?

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

Properties to set

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

## Properties

### firstMessageTimestamp?

> `optional` **firstMessageTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:28313](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28313)

MessageHistoryMetadata firstMessageTimestamp.

#### Implementation of

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md).[`firstMessageTimestamp`](../interfaces/IMessageHistoryMetadata.md#firstmessagetimestamp)

***

### historyReceivers

> **historyReceivers**: `string`[]

Defined in: [WAProto/index.d.ts:28310](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28310)

MessageHistoryMetadata historyReceivers.

#### Implementation of

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md).[`historyReceivers`](../interfaces/IMessageHistoryMetadata.md#historyreceivers)

***

### messageCount?

> `optional` **messageCount**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:28316](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28316)

MessageHistoryMetadata messageCount.

#### Implementation of

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md).[`messageCount`](../interfaces/IMessageHistoryMetadata.md#messagecount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28386](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28386)

Converts this MessageHistoryMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:28323](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28323)

Creates a new MessageHistoryMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

Properties to set

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

MessageHistoryMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:28349](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28349)

Decodes a MessageHistoryMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

MessageHistoryMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:28358](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28358)

Decodes a MessageHistoryMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

MessageHistoryMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28331](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28331)

Encodes the specified MessageHistoryMetadata message. Does not implicitly [verify](MessageHistoryMetadata.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

MessageHistoryMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28339](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28339)

Encodes the specified MessageHistoryMetadata message, length delimited. Does not implicitly [verify](MessageHistoryMetadata.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

MessageHistoryMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:28372](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28372)

Creates a MessageHistoryMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

MessageHistoryMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:28393](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28393)

Gets the default type url for MessageHistoryMetadata

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

Defined in: [WAProto/index.d.ts:28380](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28380)

Creates a plain object from a MessageHistoryMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

MessageHistoryMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28365](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L28365)

Verifies a MessageHistoryMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
