# Class: KeepInChat

Defined in: [WAProto/index.d.ts:16808](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16808)

Represents a KeepInChat.

## Implements

- [`IKeepInChat`](../interfaces/IKeepInChat.md)

## Constructors

### new KeepInChat()

> **new KeepInChat**(`properties`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:16814](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16814)

Constructs a new KeepInChat.

#### Parameters

##### properties?

[`IKeepInChat`](../interfaces/IKeepInChat.md)

Properties to set

#### Returns

[`KeepInChat`](KeepInChat.md)

## Properties

### clientTimestampMs?

> `optional` **clientTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:16829](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16829)

KeepInChat clientTimestampMs.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`clientTimestampMs`](../interfaces/IKeepInChat.md#clienttimestampms)

***

### deviceJid?

> `optional` **deviceJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16826](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16826)

KeepInChat deviceJid.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`deviceJid`](../interfaces/IKeepInChat.md#devicejid)

***

### keepType?

> `optional` **keepType**: `null` \| [`KeepType`](../enumerations/KeepType.md)

Defined in: [WAProto/index.d.ts:16817](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16817)

KeepInChat keepType.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`keepType`](../interfaces/IKeepInChat.md#keeptype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:16823](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16823)

KeepInChat key.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`key`](../interfaces/IKeepInChat.md#key)

***

### serverTimestamp?

> `optional` **serverTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:16820](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16820)

KeepInChat serverTimestamp.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`serverTimestamp`](../interfaces/IKeepInChat.md#servertimestamp)

***

### serverTimestampMs?

> `optional` **serverTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:16832](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16832)

KeepInChat serverTimestampMs.

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`serverTimestampMs`](../interfaces/IKeepInChat.md#servertimestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16902](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16902)

Converts this KeepInChat to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:16839](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16839)

Creates a new KeepInChat instance using the specified properties.

#### Parameters

##### properties?

[`IKeepInChat`](../interfaces/IKeepInChat.md)

Properties to set

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:16865](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16865)

Decodes a KeepInChat message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:16874](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16874)

Decodes a KeepInChat message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16847](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16847)

Encodes the specified KeepInChat message. Does not implicitly [verify](KeepInChat.md#verify) messages.

#### Parameters

##### message

[`IKeepInChat`](../interfaces/IKeepInChat.md)

KeepInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16855](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16855)

Encodes the specified KeepInChat message, length delimited. Does not implicitly [verify](KeepInChat.md#verify) messages.

#### Parameters

##### message

[`IKeepInChat`](../interfaces/IKeepInChat.md)

KeepInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:16888](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16888)

Creates a KeepInChat message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeepInChat`](KeepInChat.md)

KeepInChat

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:16909](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16909)

Gets the default type url for KeepInChat

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

Defined in: [WAProto/index.d.ts:16896](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16896)

Creates a plain object from a KeepInChat message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeepInChat`](KeepInChat.md)

KeepInChat

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16881](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L16881)

Verifies a KeepInChat message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
