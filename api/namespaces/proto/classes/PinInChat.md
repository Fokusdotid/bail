# Class: PinInChat

Defined in: [WAProto/index.d.ts:39048](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39048)

Represents a PinInChat.

## Implements

- [`IPinInChat`](../interfaces/IPinInChat.md)

## Constructors

### new PinInChat()

> **new PinInChat**(`properties`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:39054](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39054)

Constructs a new PinInChat.

#### Parameters

##### properties?

[`IPinInChat`](../interfaces/IPinInChat.md)

Properties to set

#### Returns

[`PinInChat`](PinInChat.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:39060](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39060)

PinInChat key.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`key`](../interfaces/IPinInChat.md#key)

***

### messageAddOnContextInfo?

> `optional` **messageAddOnContextInfo**: `null` \| [`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:39069](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39069)

PinInChat messageAddOnContextInfo.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`messageAddOnContextInfo`](../interfaces/IPinInChat.md#messageaddoncontextinfo)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:39063](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39063)

PinInChat senderTimestampMs.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`senderTimestampMs`](../interfaces/IPinInChat.md#sendertimestampms)

***

### serverTimestampMs?

> `optional` **serverTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:39066](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39066)

PinInChat serverTimestampMs.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`serverTimestampMs`](../interfaces/IPinInChat.md#servertimestampms)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/PinInChat/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:39057](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39057)

PinInChat type.

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`type`](../interfaces/IPinInChat.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:39139](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39139)

Converts this PinInChat to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:39076](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39076)

Creates a new PinInChat instance using the specified properties.

#### Parameters

##### properties?

[`IPinInChat`](../interfaces/IPinInChat.md)

Properties to set

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:39102](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39102)

Decodes a PinInChat message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:39111](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39111)

Decodes a PinInChat message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39084](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39084)

Encodes the specified PinInChat message. Does not implicitly [verify](PinInChat.md#verify) messages.

#### Parameters

##### message

[`IPinInChat`](../interfaces/IPinInChat.md)

PinInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39092](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39092)

Encodes the specified PinInChat message, length delimited. Does not implicitly [verify](PinInChat.md#verify) messages.

#### Parameters

##### message

[`IPinInChat`](../interfaces/IPinInChat.md)

PinInChat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:39125](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39125)

Creates a PinInChat message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PinInChat`](PinInChat.md)

PinInChat

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:39146](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39146)

Gets the default type url for PinInChat

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

Defined in: [WAProto/index.d.ts:39133](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39133)

Creates a plain object from a PinInChat message. Also converts values to other types if specified.

#### Parameters

##### message

[`PinInChat`](PinInChat.md)

PinInChat

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:39118](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L39118)

Verifies a PinInChat message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
