# Class: BotMemoryFact

Defined in: [WAProto/index.d.ts:4465](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4465)

Represents a BotMemoryFact.

## Implements

- [`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

## Constructors

### new BotMemoryFact()

> **new BotMemoryFact**(`properties`?): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:4471](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4471)

Constructs a new BotMemoryFact.

#### Parameters

##### properties?

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

Properties to set

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

## Properties

### fact?

> `optional` **fact**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4474](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4474)

BotMemoryFact fact.

#### Implementation of

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md).[`fact`](../interfaces/IBotMemoryFact.md#fact)

***

### factId?

> `optional` **factId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4477](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4477)

BotMemoryFact factId.

#### Implementation of

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md).[`factId`](../interfaces/IBotMemoryFact.md#factid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4547](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4547)

Converts this BotMemoryFact to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:4484](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4484)

Creates a new BotMemoryFact instance using the specified properties.

#### Parameters

##### properties?

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

Properties to set

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

BotMemoryFact instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:4510](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4510)

Decodes a BotMemoryFact message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

BotMemoryFact

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:4519](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4519)

Decodes a BotMemoryFact message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

BotMemoryFact

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4492](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4492)

Encodes the specified BotMemoryFact message. Does not implicitly [verify](BotMemoryFact.md#verify) messages.

#### Parameters

##### message

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

BotMemoryFact message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4500](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4500)

Encodes the specified BotMemoryFact message, length delimited. Does not implicitly [verify](BotMemoryFact.md#verify) messages.

#### Parameters

##### message

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

BotMemoryFact message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:4533](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4533)

Creates a BotMemoryFact message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

BotMemoryFact

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4554](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4554)

Gets the default type url for BotMemoryFact

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

Defined in: [WAProto/index.d.ts:4541](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4541)

Creates a plain object from a BotMemoryFact message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotMemoryFact`](BotMemoryFact.md)

BotMemoryFact

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4526](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4526)

Verifies a BotMemoryFact message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
