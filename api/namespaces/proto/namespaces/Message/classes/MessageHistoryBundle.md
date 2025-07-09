# Class: MessageHistoryBundle

Defined in: [WAProto/index.d.ts:28177](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28177)

Represents a MessageHistoryBundle.

## Implements

- [`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

## Constructors

### new MessageHistoryBundle()

> **new MessageHistoryBundle**(`properties`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:28183](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28183)

Constructs a new MessageHistoryBundle.

#### Parameters

##### properties?

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

Properties to set

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:28204](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28204)

MessageHistoryBundle contextInfo.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`contextInfo`](../interfaces/IMessageHistoryBundle.md#contextinfo)

***

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28198](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28198)

MessageHistoryBundle directPath.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`directPath`](../interfaces/IMessageHistoryBundle.md#directpath)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:28195](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28195)

MessageHistoryBundle fileEncSha256.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`fileEncSha256`](../interfaces/IMessageHistoryBundle.md#fileencsha256)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:28189](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28189)

MessageHistoryBundle fileSha256.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`fileSha256`](../interfaces/IMessageHistoryBundle.md#filesha256)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:28192](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28192)

MessageHistoryBundle mediaKey.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mediaKey`](../interfaces/IMessageHistoryBundle.md#mediakey)

***

### mediaKeyTimestamp?

> `optional` **mediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:28201](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28201)

MessageHistoryBundle mediaKeyTimestamp.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mediaKeyTimestamp`](../interfaces/IMessageHistoryBundle.md#mediakeytimestamp)

***

### messageHistoryMetadata?

> `optional` **messageHistoryMetadata**: `null` \| [`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:28207](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28207)

MessageHistoryBundle messageHistoryMetadata.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`messageHistoryMetadata`](../interfaces/IMessageHistoryBundle.md#messagehistorymetadata)

***

### mimetype?

> `optional` **mimetype**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28186](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28186)

MessageHistoryBundle mimetype.

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mimetype`](../interfaces/IMessageHistoryBundle.md#mimetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28277](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28277)

Converts this MessageHistoryBundle to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:28214](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28214)

Creates a new MessageHistoryBundle instance using the specified properties.

#### Parameters

##### properties?

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

Properties to set

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:28240](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28240)

Decodes a MessageHistoryBundle message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:28249](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28249)

Decodes a MessageHistoryBundle message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28222](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28222)

Encodes the specified MessageHistoryBundle message. Does not implicitly [verify](MessageHistoryBundle.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

MessageHistoryBundle message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28230](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28230)

Encodes the specified MessageHistoryBundle message, length delimited. Does not implicitly [verify](MessageHistoryBundle.md#verify) messages.

#### Parameters

##### message

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

MessageHistoryBundle message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:28263](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28263)

Creates a MessageHistoryBundle message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:28284](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28284)

Gets the default type url for MessageHistoryBundle

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

Defined in: [WAProto/index.d.ts:28271](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28271)

Creates a plain object from a MessageHistoryBundle message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageHistoryBundle`](MessageHistoryBundle.md)

MessageHistoryBundle

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28256](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L28256)

Verifies a MessageHistoryBundle message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
