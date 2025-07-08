# Class: BotModeSelectionMetadata

Defined in: [WAProto/index.d.ts:5151](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5151)

Represents a BotModeSelectionMetadata.

## Implements

- [`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

## Constructors

### new BotModeSelectionMetadata()

> **new BotModeSelectionMetadata**(`properties`?): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:5157](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5157)

Constructs a new BotModeSelectionMetadata.

#### Parameters

##### properties?

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

Properties to set

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

## Properties

### mode

> **mode**: [`BotUserSelectionMode`](../namespaces/BotModeSelectionMetadata/enumerations/BotUserSelectionMode.md)[]

Defined in: [WAProto/index.d.ts:5160](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5160)

BotModeSelectionMetadata mode.

#### Implementation of

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md).[`mode`](../interfaces/IBotModeSelectionMetadata.md#mode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5230](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5230)

Converts this BotModeSelectionMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:5167](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5167)

Creates a new BotModeSelectionMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

Properties to set

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

BotModeSelectionMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:5193](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5193)

Decodes a BotModeSelectionMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

BotModeSelectionMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:5202](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5202)

Decodes a BotModeSelectionMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

BotModeSelectionMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5175](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5175)

Encodes the specified BotModeSelectionMetadata message. Does not implicitly [verify](BotModeSelectionMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

BotModeSelectionMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5183](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5183)

Encodes the specified BotModeSelectionMetadata message, length delimited. Does not implicitly [verify](BotModeSelectionMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

BotModeSelectionMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:5216](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5216)

Creates a BotModeSelectionMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

BotModeSelectionMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5237](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5237)

Gets the default type url for BotModeSelectionMetadata

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

Defined in: [WAProto/index.d.ts:5224](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5224)

Creates a plain object from a BotModeSelectionMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

BotModeSelectionMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5209](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L5209)

Verifies a BotModeSelectionMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
