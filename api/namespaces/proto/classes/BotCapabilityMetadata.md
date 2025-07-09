# Class: BotCapabilityMetadata

Defined in: [WAProto/index.d.ts:3856](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3856)

Represents a BotCapabilityMetadata.

## Implements

- [`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

## Constructors

### new BotCapabilityMetadata()

> **new BotCapabilityMetadata**(`properties`?): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:3862](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3862)

Constructs a new BotCapabilityMetadata.

#### Parameters

##### properties?

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

Properties to set

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

## Properties

### capabilities

> **capabilities**: [`BotCapabilityType`](../namespaces/BotCapabilityMetadata/enumerations/BotCapabilityType.md)[]

Defined in: [WAProto/index.d.ts:3865](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3865)

BotCapabilityMetadata capabilities.

#### Implementation of

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md).[`capabilities`](../interfaces/IBotCapabilityMetadata.md#capabilities)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3935](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3935)

Converts this BotCapabilityMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:3872](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3872)

Creates a new BotCapabilityMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

Properties to set

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

BotCapabilityMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:3898](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3898)

Decodes a BotCapabilityMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

BotCapabilityMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:3907](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3907)

Decodes a BotCapabilityMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

BotCapabilityMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3880](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3880)

Encodes the specified BotCapabilityMetadata message. Does not implicitly [verify](BotCapabilityMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

BotCapabilityMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3888](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3888)

Encodes the specified BotCapabilityMetadata message, length delimited. Does not implicitly [verify](BotCapabilityMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

BotCapabilityMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:3921](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3921)

Creates a BotCapabilityMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

BotCapabilityMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3942](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3942)

Gets the default type url for BotCapabilityMetadata

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

Defined in: [WAProto/index.d.ts:3929](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3929)

Creates a plain object from a BotCapabilityMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

BotCapabilityMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3914](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L3914)

Verifies a BotCapabilityMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
