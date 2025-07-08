# Class: PollUpdate

Defined in: [WAProto/index.d.ts:39494](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39494)

Represents a PollUpdate.

## Implements

- [`IPollUpdate`](../interfaces/IPollUpdate.md)

## Constructors

### new PollUpdate()

> **new PollUpdate**(`properties`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:39500](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39500)

Constructs a new PollUpdate.

#### Parameters

##### properties?

[`IPollUpdate`](../interfaces/IPollUpdate.md)

Properties to set

#### Returns

[`PollUpdate`](PollUpdate.md)

## Properties

### pollUpdateMessageKey?

> `optional` **pollUpdateMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:39503](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39503)

PollUpdate pollUpdateMessageKey.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`pollUpdateMessageKey`](../interfaces/IPollUpdate.md#pollupdatemessagekey)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:39509](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39509)

PollUpdate senderTimestampMs.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`senderTimestampMs`](../interfaces/IPollUpdate.md#sendertimestampms)

***

### serverTimestampMs?

> `optional` **serverTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:39512](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39512)

PollUpdate serverTimestampMs.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`serverTimestampMs`](../interfaces/IPollUpdate.md#servertimestampms)

***

### unread?

> `optional` **unread**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:39515](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39515)

PollUpdate unread.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`unread`](../interfaces/IPollUpdate.md#unread)

***

### vote?

> `optional` **vote**: `null` \| [`IPollVoteMessage`](../namespaces/Message/interfaces/IPollVoteMessage.md)

Defined in: [WAProto/index.d.ts:39506](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39506)

PollUpdate vote.

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`vote`](../interfaces/IPollUpdate.md#vote)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:39585](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39585)

Converts this PollUpdate to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:39522](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39522)

Creates a new PollUpdate instance using the specified properties.

#### Parameters

##### properties?

[`IPollUpdate`](../interfaces/IPollUpdate.md)

Properties to set

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:39548](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39548)

Decodes a PollUpdate message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:39557](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39557)

Decodes a PollUpdate message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39530](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39530)

Encodes the specified PollUpdate message. Does not implicitly [verify](PollUpdate.md#verify) messages.

#### Parameters

##### message

[`IPollUpdate`](../interfaces/IPollUpdate.md)

PollUpdate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39538](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39538)

Encodes the specified PollUpdate message, length delimited. Does not implicitly [verify](PollUpdate.md#verify) messages.

#### Parameters

##### message

[`IPollUpdate`](../interfaces/IPollUpdate.md)

PollUpdate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:39571](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39571)

Creates a PollUpdate message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollUpdate`](PollUpdate.md)

PollUpdate

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:39592](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39592)

Gets the default type url for PollUpdate

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

Defined in: [WAProto/index.d.ts:39579](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39579)

Creates a plain object from a PollUpdate message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollUpdate`](PollUpdate.md)

PollUpdate

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:39564](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39564)

Verifies a PollUpdate message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
