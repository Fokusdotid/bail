# Class: Header

Defined in: [WAProto/index.d.ts:25535](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25535)

Represents a Header.

## Implements

- [`IHeader`](../interfaces/IHeader.md)

## Constructors

### new Header()

> **new Header**(`properties`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:25541](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25541)

Constructs a new Header.

#### Parameters

##### properties?

[`IHeader`](../interfaces/IHeader.md)

Properties to set

#### Returns

[`Header`](Header.md)

## Properties

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../../../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:25553](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25553)

Header documentMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`documentMessage`](../interfaces/IHeader.md#documentmessage)

***

### hasMediaAttachment?

> `optional` **hasMediaAttachment**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:25550](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25550)

Header hasMediaAttachment.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`hasMediaAttachment`](../interfaces/IHeader.md#hasmediaattachment)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:25556](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25556)

Header imageMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`imageMessage`](../interfaces/IHeader.md#imagemessage)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:25559](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25559)

Header jpegThumbnail.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`jpegThumbnail`](../interfaces/IHeader.md#jpegthumbnail)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../../../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:25565](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25565)

Header locationMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`locationMessage`](../interfaces/IHeader.md#locationmessage)

***

### media?

> `optional` **media**: `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"` \| `"productMessage"` \| `"jpegThumbnail"`

Defined in: [WAProto/index.d.ts:25571](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25571)

Header media.

***

### productMessage?

> `optional` **productMessage**: `null` \| [`IProductMessage`](../../../interfaces/IProductMessage.md)

Defined in: [WAProto/index.d.ts:25568](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25568)

Header productMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`productMessage`](../interfaces/IHeader.md#productmessage)

***

### subtitle?

> `optional` **subtitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25547](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25547)

Header subtitle.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`subtitle`](../interfaces/IHeader.md#subtitle)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25544](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25544)

Header title.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`title`](../interfaces/IHeader.md#title)

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../../../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:25562](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25562)

Header videoMessage.

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`videoMessage`](../interfaces/IHeader.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25641](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25641)

Converts this Header to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:25578](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25578)

Creates a new Header instance using the specified properties.

#### Parameters

##### properties?

[`IHeader`](../interfaces/IHeader.md)

Properties to set

#### Returns

[`Header`](Header.md)

Header instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:25604](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25604)

Decodes a Header message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Header`](Header.md)

Header

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:25613](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25613)

Decodes a Header message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Header`](Header.md)

Header

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25586](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25586)

Encodes the specified Header message. Does not implicitly [verify](Header.md#verify) messages.

#### Parameters

##### message

[`IHeader`](../interfaces/IHeader.md)

Header message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25594](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25594)

Encodes the specified Header message, length delimited. Does not implicitly [verify](Header.md#verify) messages.

#### Parameters

##### message

[`IHeader`](../interfaces/IHeader.md)

Header message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:25627](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25627)

Creates a Header message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Header`](Header.md)

Header

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:25648](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25648)

Gets the default type url for Header

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

Defined in: [WAProto/index.d.ts:25635](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25635)

Creates a plain object from a Header message. Also converts values to other types if specified.

#### Parameters

##### message

[`Header`](Header.md)

Header

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25620](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L25620)

Verifies a Header message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
