# Class: BotMemuMetadata

Defined in: [WAProto/index.d.ts:4674](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4674)

Represents a BotMemuMetadata.

## Implements

- [`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

## Constructors

### new BotMemuMetadata()

> **new BotMemuMetadata**(`properties`?): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:4680](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4680)

Constructs a new BotMemuMetadata.

#### Parameters

##### properties?

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

Properties to set

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

## Properties

### faceImages

> **faceImages**: [`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)[]

Defined in: [WAProto/index.d.ts:4683](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4683)

BotMemuMetadata faceImages.

#### Implementation of

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md).[`faceImages`](../interfaces/IBotMemuMetadata.md#faceimages)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4753](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4753)

Converts this BotMemuMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:4690](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4690)

Creates a new BotMemuMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

Properties to set

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

BotMemuMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:4716](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4716)

Decodes a BotMemuMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

BotMemuMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:4725](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4725)

Decodes a BotMemuMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

BotMemuMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4698](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4698)

Encodes the specified BotMemuMetadata message. Does not implicitly [verify](BotMemuMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

BotMemuMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4706](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4706)

Encodes the specified BotMemuMetadata message, length delimited. Does not implicitly [verify](BotMemuMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

BotMemuMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:4739](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4739)

Creates a BotMemuMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

BotMemuMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4760](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4760)

Gets the default type url for BotMemuMetadata

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

Defined in: [WAProto/index.d.ts:4747](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4747)

Creates a plain object from a BotMemuMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotMemuMetadata`](BotMemuMetadata.md)

BotMemuMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4732](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L4732)

Verifies a BotMemuMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
