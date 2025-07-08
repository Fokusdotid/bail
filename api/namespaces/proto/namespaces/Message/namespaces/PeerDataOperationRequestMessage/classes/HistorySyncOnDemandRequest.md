# Class: HistorySyncOnDemandRequest

Defined in: [WAProto/index.d.ts:29506](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29506)

Represents a HistorySyncOnDemandRequest.

## Implements

- [`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

## Constructors

### new HistorySyncOnDemandRequest()

> **new HistorySyncOnDemandRequest**(`properties`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29512](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29512)

Constructs a new HistorySyncOnDemandRequest.

#### Parameters

##### properties?

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

Properties to set

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

## Properties

### accountLid?

> `optional` **accountLid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:29530](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29530)

HistorySyncOnDemandRequest accountLid.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`accountLid`](../interfaces/IHistorySyncOnDemandRequest.md#accountlid)

***

### chatJid?

> `optional` **chatJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:29515](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29515)

HistorySyncOnDemandRequest chatJid.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`chatJid`](../interfaces/IHistorySyncOnDemandRequest.md#chatjid)

***

### oldestMsgFromMe?

> `optional` **oldestMsgFromMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:29521](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29521)

HistorySyncOnDemandRequest oldestMsgFromMe.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgFromMe`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgfromme)

***

### oldestMsgId?

> `optional` **oldestMsgId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:29518](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29518)

HistorySyncOnDemandRequest oldestMsgId.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgId`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgid)

***

### oldestMsgTimestampMs?

> `optional` **oldestMsgTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:29527](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29527)

HistorySyncOnDemandRequest oldestMsgTimestampMs.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgTimestampMs`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgtimestampms)

***

### onDemandMsgCount?

> `optional` **onDemandMsgCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:29524](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29524)

HistorySyncOnDemandRequest onDemandMsgCount.

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`onDemandMsgCount`](../interfaces/IHistorySyncOnDemandRequest.md#ondemandmsgcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29600](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29600)

Converts this HistorySyncOnDemandRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29537](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29537)

Creates a new HistorySyncOnDemandRequest instance using the specified properties.

#### Parameters

##### properties?

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

Properties to set

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29563](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29563)

Decodes a HistorySyncOnDemandRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29572](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29572)

Decodes a HistorySyncOnDemandRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29545](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29545)

Encodes the specified HistorySyncOnDemandRequest message. Does not implicitly [verify](HistorySyncOnDemandRequest.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29553](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29553)

Encodes the specified HistorySyncOnDemandRequest message, length delimited. Does not implicitly [verify](HistorySyncOnDemandRequest.md#verify) messages.

#### Parameters

##### message

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29586](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29586)

Creates a HistorySyncOnDemandRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:29607](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29607)

Gets the default type url for HistorySyncOnDemandRequest

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

Defined in: [WAProto/index.d.ts:29594](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29594)

Creates a plain object from a HistorySyncOnDemandRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

HistorySyncOnDemandRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29579](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L29579)

Verifies a HistorySyncOnDemandRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
