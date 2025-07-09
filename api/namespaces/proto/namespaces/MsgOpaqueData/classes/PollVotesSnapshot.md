# Class: PollVotesSnapshot

Defined in: [WAProto/index.d.ts:37140](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37140)

Represents a PollVotesSnapshot.

## Implements

- [`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

## Constructors

### new PollVotesSnapshot()

> **new PollVotesSnapshot**(`properties`?): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:37146](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37146)

Constructs a new PollVotesSnapshot.

#### Parameters

##### properties?

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

Properties to set

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

## Properties

### pollVotes

> **pollVotes**: [`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md)[]

Defined in: [WAProto/index.d.ts:37149](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37149)

PollVotesSnapshot pollVotes.

#### Implementation of

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md).[`pollVotes`](../interfaces/IPollVotesSnapshot.md#pollvotes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37219](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37219)

Converts this PollVotesSnapshot to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:37156](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37156)

Creates a new PollVotesSnapshot instance using the specified properties.

#### Parameters

##### properties?

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

Properties to set

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

PollVotesSnapshot instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:37182](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37182)

Decodes a PollVotesSnapshot message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

PollVotesSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:37191](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37191)

Decodes a PollVotesSnapshot message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

PollVotesSnapshot

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37164](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37164)

Encodes the specified PollVotesSnapshot message. Does not implicitly [verify](PollVotesSnapshot.md#verify) messages.

#### Parameters

##### message

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

PollVotesSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37172](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37172)

Encodes the specified PollVotesSnapshot message, length delimited. Does not implicitly [verify](PollVotesSnapshot.md#verify) messages.

#### Parameters

##### message

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

PollVotesSnapshot message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:37205](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37205)

Creates a PollVotesSnapshot message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

PollVotesSnapshot

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:37226](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37226)

Gets the default type url for PollVotesSnapshot

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

Defined in: [WAProto/index.d.ts:37213](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37213)

Creates a plain object from a PollVotesSnapshot message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollVotesSnapshot`](PollVotesSnapshot.md)

PollVotesSnapshot

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:37198](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L37198)

Verifies a PollVotesSnapshot message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
