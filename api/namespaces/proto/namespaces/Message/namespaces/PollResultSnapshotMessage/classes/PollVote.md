# Class: PollVote

Defined in: [WAProto/index.d.ts:31768](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31768)

Represents a PollVote.

## Implements

- [`IPollVote`](../interfaces/IPollVote.md)

## Constructors

### new PollVote()

> **new PollVote**(`properties`?): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:31774](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31774)

Constructs a new PollVote.

#### Parameters

##### properties?

[`IPollVote`](../interfaces/IPollVote.md)

Properties to set

#### Returns

[`PollVote`](PollVote.md)

## Properties

### optionName?

> `optional` **optionName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:31777](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31777)

PollVote optionName.

#### Implementation of

[`IPollVote`](../interfaces/IPollVote.md).[`optionName`](../interfaces/IPollVote.md#optionname)

***

### optionVoteCount?

> `optional` **optionVoteCount**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:31780](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31780)

PollVote optionVoteCount.

#### Implementation of

[`IPollVote`](../interfaces/IPollVote.md).[`optionVoteCount`](../interfaces/IPollVote.md#optionvotecount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31850](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31850)

Converts this PollVote to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:31787](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31787)

Creates a new PollVote instance using the specified properties.

#### Parameters

##### properties?

[`IPollVote`](../interfaces/IPollVote.md)

Properties to set

#### Returns

[`PollVote`](PollVote.md)

PollVote instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:31813](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31813)

Decodes a PollVote message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollVote`](PollVote.md)

PollVote

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:31822](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31822)

Decodes a PollVote message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollVote`](PollVote.md)

PollVote

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31795](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31795)

Encodes the specified PollVote message. Does not implicitly [verify](PollVote.md#verify) messages.

#### Parameters

##### message

[`IPollVote`](../interfaces/IPollVote.md)

PollVote message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31803](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31803)

Encodes the specified PollVote message, length delimited. Does not implicitly [verify](PollVote.md#verify) messages.

#### Parameters

##### message

[`IPollVote`](../interfaces/IPollVote.md)

PollVote message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:31836](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31836)

Creates a PollVote message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollVote`](PollVote.md)

PollVote

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:31857](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31857)

Gets the default type url for PollVote

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

Defined in: [WAProto/index.d.ts:31844](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31844)

Creates a plain object from a PollVote message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollVote`](PollVote.md)

PollVote

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31829](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L31829)

Verifies a PollVote message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
