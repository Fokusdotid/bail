# Class: ButtonsMessage

Defined in: [WAProto/index.d.ts:20285](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20285)

Represents a ButtonsMessage.

## Implements

- [`IButtonsMessage`](../interfaces/IButtonsMessage.md)

## Constructors

### new ButtonsMessage()

> **new ButtonsMessage**(`properties`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:20291](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20291)

Constructs a new ButtonsMessage.

#### Parameters

##### properties?

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

Properties to set

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

## Properties

### buttons

> **buttons**: [`IButton`](../namespaces/ButtonsMessage/interfaces/IButton.md)[]

Defined in: [WAProto/index.d.ts:20303](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20303)

ButtonsMessage buttons.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`buttons`](../interfaces/IButtonsMessage.md#buttons)

***

### contentText?

> `optional` **contentText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20294](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20294)

ButtonsMessage contentText.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`contentText`](../interfaces/IButtonsMessage.md#contenttext)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:20300](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20300)

ButtonsMessage contextInfo.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`contextInfo`](../interfaces/IButtonsMessage.md#contextinfo)

***

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:20312](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20312)

ButtonsMessage documentMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`documentMessage`](../interfaces/IButtonsMessage.md#documentmessage)

***

### footerText?

> `optional` **footerText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20297](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20297)

ButtonsMessage footerText.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`footerText`](../interfaces/IButtonsMessage.md#footertext)

***

### header?

> `optional` **header**: `"text"` \| `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"`

Defined in: [WAProto/index.d.ts:20324](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20324)

ButtonsMessage header.

***

### headerType?

> `optional` **headerType**: `null` \| [`HeaderType`](../namespaces/ButtonsMessage/enumerations/HeaderType.md)

Defined in: [WAProto/index.d.ts:20306](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20306)

ButtonsMessage headerType.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`headerType`](../interfaces/IButtonsMessage.md#headertype)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:20315](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20315)

ButtonsMessage imageMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`imageMessage`](../interfaces/IButtonsMessage.md#imagemessage)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:20321](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20321)

ButtonsMessage locationMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`locationMessage`](../interfaces/IButtonsMessage.md#locationmessage)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20309](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20309)

ButtonsMessage text.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`text`](../interfaces/IButtonsMessage.md#text)

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:20318](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20318)

ButtonsMessage videoMessage.

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`videoMessage`](../interfaces/IButtonsMessage.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20394](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20394)

Converts this ButtonsMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:20331](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20331)

Creates a new ButtonsMessage instance using the specified properties.

#### Parameters

##### properties?

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

Properties to set

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:20357](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20357)

Decodes a ButtonsMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:20366](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20366)

Decodes a ButtonsMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20339](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20339)

Encodes the specified ButtonsMessage message. Does not implicitly [verify](ButtonsMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

ButtonsMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20347](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20347)

Encodes the specified ButtonsMessage message, length delimited. Does not implicitly [verify](ButtonsMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

ButtonsMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:20380](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20380)

Creates a ButtonsMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:20401](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20401)

Gets the default type url for ButtonsMessage

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

Defined in: [WAProto/index.d.ts:20388](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20388)

Creates a plain object from a ButtonsMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ButtonsMessage`](ButtonsMessage.md)

ButtonsMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20373](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20373)

Verifies a ButtonsMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
