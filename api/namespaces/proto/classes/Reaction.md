# Class: Reaction

Defined in: [WAProto/index.d.ts:40414](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40414)

Represents a Reaction.

## Implements

- [`IReaction`](../interfaces/IReaction.md)

## Constructors

### new Reaction()

> **new Reaction**(`properties`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:40420](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40420)

Constructs a new Reaction.

#### Parameters

##### properties?

[`IReaction`](../interfaces/IReaction.md)

Properties to set

#### Returns

[`Reaction`](Reaction.md)

## Properties

### groupingKey?

> `optional` **groupingKey**: `null` \| `string`

Defined in: [WAProto/index.d.ts:40429](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40429)

Reaction groupingKey.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`groupingKey`](../interfaces/IReaction.md#groupingkey)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:40423](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40423)

Reaction key.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`key`](../interfaces/IReaction.md#key)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:40432](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40432)

Reaction senderTimestampMs.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`senderTimestampMs`](../interfaces/IReaction.md#sendertimestampms)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:40426](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40426)

Reaction text.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`text`](../interfaces/IReaction.md#text)

***

### unread?

> `optional` **unread**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:40435](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40435)

Reaction unread.

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`unread`](../interfaces/IReaction.md#unread)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:40505](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40505)

Converts this Reaction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:40442](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40442)

Creates a new Reaction instance using the specified properties.

#### Parameters

##### properties?

[`IReaction`](../interfaces/IReaction.md)

Properties to set

#### Returns

[`Reaction`](Reaction.md)

Reaction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:40468](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40468)

Decodes a Reaction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Reaction`](Reaction.md)

Reaction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:40477](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40477)

Decodes a Reaction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Reaction`](Reaction.md)

Reaction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40450](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40450)

Encodes the specified Reaction message. Does not implicitly [verify](Reaction.md#verify) messages.

#### Parameters

##### message

[`IReaction`](../interfaces/IReaction.md)

Reaction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40458](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40458)

Encodes the specified Reaction message, length delimited. Does not implicitly [verify](Reaction.md#verify) messages.

#### Parameters

##### message

[`IReaction`](../interfaces/IReaction.md)

Reaction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:40491](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40491)

Creates a Reaction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Reaction`](Reaction.md)

Reaction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:40512](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40512)

Gets the default type url for Reaction

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

Defined in: [WAProto/index.d.ts:40499](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40499)

Creates a plain object from a Reaction message. Also converts values to other types if specified.

#### Parameters

##### message

[`Reaction`](Reaction.md)

Reaction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:40484](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L40484)

Verifies a Reaction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
