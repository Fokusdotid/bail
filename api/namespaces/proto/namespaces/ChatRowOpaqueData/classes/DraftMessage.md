# Class: DraftMessage

Defined in: [WAProto/index.d.ts:8365](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8365)

Represents a DraftMessage.

## Implements

- [`IDraftMessage`](../interfaces/IDraftMessage.md)

## Constructors

### new DraftMessage()

> **new DraftMessage**(`properties`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:8371](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8371)

Constructs a new DraftMessage.

#### Parameters

##### properties?

[`IDraftMessage`](../interfaces/IDraftMessage.md)

Properties to set

#### Returns

[`DraftMessage`](DraftMessage.md)

## Properties

### ctwaContext?

> `optional` **ctwaContext**: `null` \| [`ICtwaContextData`](../namespaces/DraftMessage/interfaces/ICtwaContextData.md)

Defined in: [WAProto/index.d.ts:8383](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8383)

DraftMessage ctwaContext.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`ctwaContext`](../interfaces/IDraftMessage.md#ctwacontext)

***

### ctwaContextLinkData?

> `optional` **ctwaContextLinkData**: `null` \| [`ICtwaContextLinkData`](../namespaces/DraftMessage/interfaces/ICtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:8380](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8380)

DraftMessage ctwaContextLinkData.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`ctwaContextLinkData`](../interfaces/IDraftMessage.md#ctwacontextlinkdata)

***

### omittedUrl?

> `optional` **omittedUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8377](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8377)

DraftMessage omittedUrl.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`omittedUrl`](../interfaces/IDraftMessage.md#omittedurl)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8374](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8374)

DraftMessage text.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`text`](../interfaces/IDraftMessage.md#text)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8386](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8386)

DraftMessage timestamp.

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`timestamp`](../interfaces/IDraftMessage.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8456](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8456)

Converts this DraftMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:8393](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8393)

Creates a new DraftMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDraftMessage`](../interfaces/IDraftMessage.md)

Properties to set

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:8419](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8419)

Decodes a DraftMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:8428](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8428)

Decodes a DraftMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8401](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8401)

Encodes the specified DraftMessage message. Does not implicitly [verify](DraftMessage.md#verify) messages.

#### Parameters

##### message

[`IDraftMessage`](../interfaces/IDraftMessage.md)

DraftMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8409](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8409)

Encodes the specified DraftMessage message, length delimited. Does not implicitly [verify](DraftMessage.md#verify) messages.

#### Parameters

##### message

[`IDraftMessage`](../interfaces/IDraftMessage.md)

DraftMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:8442](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8442)

Creates a DraftMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DraftMessage`](DraftMessage.md)

DraftMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8463](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8463)

Gets the default type url for DraftMessage

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

Defined in: [WAProto/index.d.ts:8450](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8450)

Creates a plain object from a DraftMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DraftMessage`](DraftMessage.md)

DraftMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8435](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L8435)

Verifies a DraftMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
