# Class: TemplateButtonReplyMessage

Defined in: [WAProto/index.d.ts:34672](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34672)

Represents a TemplateButtonReplyMessage.

## Implements

- [`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

## Constructors

### new TemplateButtonReplyMessage()

> **new TemplateButtonReplyMessage**(`properties`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:34678](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34678)

Constructs a new TemplateButtonReplyMessage.

#### Parameters

##### properties?

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

Properties to set

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:34687](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34687)

TemplateButtonReplyMessage contextInfo.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`contextInfo`](../interfaces/ITemplateButtonReplyMessage.md#contextinfo)

***

### selectedCarouselCardIndex?

> `optional` **selectedCarouselCardIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:34693](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34693)

TemplateButtonReplyMessage selectedCarouselCardIndex.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedCarouselCardIndex`](../interfaces/ITemplateButtonReplyMessage.md#selectedcarouselcardindex)

***

### selectedDisplayText?

> `optional` **selectedDisplayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:34684](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34684)

TemplateButtonReplyMessage selectedDisplayText.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedDisplayText`](../interfaces/ITemplateButtonReplyMessage.md#selecteddisplaytext)

***

### selectedId?

> `optional` **selectedId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:34681](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34681)

TemplateButtonReplyMessage selectedId.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedId`](../interfaces/ITemplateButtonReplyMessage.md#selectedid)

***

### selectedIndex?

> `optional` **selectedIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:34690](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34690)

TemplateButtonReplyMessage selectedIndex.

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedIndex`](../interfaces/ITemplateButtonReplyMessage.md#selectedindex)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34763](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34763)

Converts this TemplateButtonReplyMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:34700](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34700)

Creates a new TemplateButtonReplyMessage instance using the specified properties.

#### Parameters

##### properties?

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

Properties to set

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:34726](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34726)

Decodes a TemplateButtonReplyMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:34735](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34735)

Decodes a TemplateButtonReplyMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34708](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34708)

Encodes the specified TemplateButtonReplyMessage message. Does not implicitly [verify](TemplateButtonReplyMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

TemplateButtonReplyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34716](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34716)

Encodes the specified TemplateButtonReplyMessage message, length delimited. Does not implicitly [verify](TemplateButtonReplyMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

TemplateButtonReplyMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:34749](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34749)

Creates a TemplateButtonReplyMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:34770](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34770)

Gets the default type url for TemplateButtonReplyMessage

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

Defined in: [WAProto/index.d.ts:34757](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34757)

Creates a plain object from a TemplateButtonReplyMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

TemplateButtonReplyMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34742](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L34742)

Verifies a TemplateButtonReplyMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
