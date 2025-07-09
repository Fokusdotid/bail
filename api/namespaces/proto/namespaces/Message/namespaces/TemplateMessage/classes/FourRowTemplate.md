# Class: FourRowTemplate

Defined in: [WAProto/index.d.ts:34934](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34934)

Represents a FourRowTemplate.

## Implements

- [`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

## Constructors

### new FourRowTemplate()

> **new FourRowTemplate**(`properties`?): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:34940](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34940)

Constructs a new FourRowTemplate.

#### Parameters

##### properties?

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

Properties to set

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

## Properties

### buttons

> **buttons**: [`ITemplateButton`](../../../../../interfaces/ITemplateButton.md)[]

Defined in: [WAProto/index.d.ts:34949](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34949)

FourRowTemplate buttons.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`buttons`](../interfaces/IFourRowTemplate.md#buttons)

***

### content?

> `optional` **content**: `null` \| [`IHighlyStructuredMessage`](../../../interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:34943](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34943)

FourRowTemplate content.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`content`](../interfaces/IFourRowTemplate.md#content)

***

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../../../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:34952](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34952)

FourRowTemplate documentMessage.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`documentMessage`](../interfaces/IFourRowTemplate.md#documentmessage)

***

### footer?

> `optional` **footer**: `null` \| [`IHighlyStructuredMessage`](../../../interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:34946](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34946)

FourRowTemplate footer.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`footer`](../interfaces/IFourRowTemplate.md#footer)

***

### highlyStructuredMessage?

> `optional` **highlyStructuredMessage**: `null` \| [`IHighlyStructuredMessage`](../../../interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:34955](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34955)

FourRowTemplate highlyStructuredMessage.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`highlyStructuredMessage`](../interfaces/IFourRowTemplate.md#highlystructuredmessage)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:34958](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34958)

FourRowTemplate imageMessage.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`imageMessage`](../interfaces/IFourRowTemplate.md#imagemessage)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../../../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:34964](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34964)

FourRowTemplate locationMessage.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`locationMessage`](../interfaces/IFourRowTemplate.md#locationmessage)

***

### title?

> `optional` **title**: `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"` \| `"highlyStructuredMessage"`

Defined in: [WAProto/index.d.ts:34967](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34967)

FourRowTemplate title.

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../../../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:34961](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34961)

FourRowTemplate videoMessage.

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`videoMessage`](../interfaces/IFourRowTemplate.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35037](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L35037)

Converts this FourRowTemplate to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:34974](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34974)

Creates a new FourRowTemplate instance using the specified properties.

#### Parameters

##### properties?

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

Properties to set

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

FourRowTemplate instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:35000](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L35000)

Decodes a FourRowTemplate message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

FourRowTemplate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:35009](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L35009)

Decodes a FourRowTemplate message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

FourRowTemplate

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34982](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34982)

Encodes the specified FourRowTemplate message. Does not implicitly [verify](FourRowTemplate.md#verify) messages.

#### Parameters

##### message

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

FourRowTemplate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34990](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L34990)

Encodes the specified FourRowTemplate message, length delimited. Does not implicitly [verify](FourRowTemplate.md#verify) messages.

#### Parameters

##### message

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

FourRowTemplate message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:35023](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L35023)

Creates a FourRowTemplate message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

FourRowTemplate

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:35044](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L35044)

Gets the default type url for FourRowTemplate

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

Defined in: [WAProto/index.d.ts:35031](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L35031)

Creates a plain object from a FourRowTemplate message. Also converts values to other types if specified.

#### Parameters

##### message

[`FourRowTemplate`](FourRowTemplate.md)

FourRowTemplate

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35016](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L35016)

Verifies a FourRowTemplate message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
