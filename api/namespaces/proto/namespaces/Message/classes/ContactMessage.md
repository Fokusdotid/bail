# Class: ContactMessage

Defined in: [WAProto/index.d.ts:21800](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21800)

Represents a ContactMessage.

## Implements

- [`IContactMessage`](../interfaces/IContactMessage.md)

## Constructors

### new ContactMessage()

> **new ContactMessage**(`properties`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:21806](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21806)

Constructs a new ContactMessage.

#### Parameters

##### properties?

[`IContactMessage`](../interfaces/IContactMessage.md)

Properties to set

#### Returns

[`ContactMessage`](ContactMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:21815](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21815)

ContactMessage contextInfo.

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`contextInfo`](../interfaces/IContactMessage.md#contextinfo)

***

### displayName?

> `optional` **displayName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21809](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21809)

ContactMessage displayName.

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`displayName`](../interfaces/IContactMessage.md#displayname)

***

### vcard?

> `optional` **vcard**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21812](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21812)

ContactMessage vcard.

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`vcard`](../interfaces/IContactMessage.md#vcard)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21885](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21885)

Converts this ContactMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:21822](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21822)

Creates a new ContactMessage instance using the specified properties.

#### Parameters

##### properties?

[`IContactMessage`](../interfaces/IContactMessage.md)

Properties to set

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:21848](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21848)

Decodes a ContactMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:21857](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21857)

Decodes a ContactMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21830](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21830)

Encodes the specified ContactMessage message. Does not implicitly [verify](ContactMessage.md#verify) messages.

#### Parameters

##### message

[`IContactMessage`](../interfaces/IContactMessage.md)

ContactMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21838](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21838)

Encodes the specified ContactMessage message, length delimited. Does not implicitly [verify](ContactMessage.md#verify) messages.

#### Parameters

##### message

[`IContactMessage`](../interfaces/IContactMessage.md)

ContactMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:21871](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21871)

Creates a ContactMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ContactMessage`](ContactMessage.md)

ContactMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21892](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21892)

Gets the default type url for ContactMessage

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

Defined in: [WAProto/index.d.ts:21879](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21879)

Creates a plain object from a ContactMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ContactMessage`](ContactMessage.md)

ContactMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21864](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L21864)

Verifies a ContactMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
