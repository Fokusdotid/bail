# Class: MsgRowOpaqueData

Defined in: [WAProto/index.d.ts:37241](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37241)

Represents a MsgRowOpaqueData.

## Implements

- [`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

## Constructors

### new MsgRowOpaqueData()

> **new MsgRowOpaqueData**(`properties`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:37247](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37247)

Constructs a new MsgRowOpaqueData.

#### Parameters

##### properties?

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

Properties to set

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

## Properties

### currentMsg?

> `optional` **currentMsg**: `null` \| [`IMsgOpaqueData`](../interfaces/IMsgOpaqueData.md)

Defined in: [WAProto/index.d.ts:37250](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37250)

MsgRowOpaqueData currentMsg.

#### Implementation of

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md).[`currentMsg`](../interfaces/IMsgRowOpaqueData.md#currentmsg)

***

### quotedMsg?

> `optional` **quotedMsg**: `null` \| [`IMsgOpaqueData`](../interfaces/IMsgOpaqueData.md)

Defined in: [WAProto/index.d.ts:37253](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37253)

MsgRowOpaqueData quotedMsg.

#### Implementation of

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md).[`quotedMsg`](../interfaces/IMsgRowOpaqueData.md#quotedmsg)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37323](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37323)

Converts this MsgRowOpaqueData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:37260](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37260)

Creates a new MsgRowOpaqueData instance using the specified properties.

#### Parameters

##### properties?

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

Properties to set

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:37286](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37286)

Decodes a MsgRowOpaqueData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:37295](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37295)

Decodes a MsgRowOpaqueData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37268](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37268)

Encodes the specified MsgRowOpaqueData message. Does not implicitly [verify](MsgRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

MsgRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37276](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37276)

Encodes the specified MsgRowOpaqueData message, length delimited. Does not implicitly [verify](MsgRowOpaqueData.md#verify) messages.

#### Parameters

##### message

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

MsgRowOpaqueData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:37309](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37309)

Creates a MsgRowOpaqueData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:37330](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37330)

Gets the default type url for MsgRowOpaqueData

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

Defined in: [WAProto/index.d.ts:37317](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37317)

Creates a plain object from a MsgRowOpaqueData message. Also converts values to other types if specified.

#### Parameters

##### message

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

MsgRowOpaqueData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:37302](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37302)

Verifies a MsgRowOpaqueData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
