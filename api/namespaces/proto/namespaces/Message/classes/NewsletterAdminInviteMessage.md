# Class: NewsletterAdminInviteMessage

Defined in: [WAProto/index.d.ts:28522](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28522)

Represents a NewsletterAdminInviteMessage.

## Implements

- [`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

## Constructors

### new NewsletterAdminInviteMessage()

> **new NewsletterAdminInviteMessage**(`properties`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:28528](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28528)

Constructs a new NewsletterAdminInviteMessage.

#### Parameters

##### properties?

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

Properties to set

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

## Properties

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28540](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28540)

NewsletterAdminInviteMessage caption.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`caption`](../interfaces/INewsletterAdminInviteMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:28546](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28546)

NewsletterAdminInviteMessage contextInfo.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`contextInfo`](../interfaces/INewsletterAdminInviteMessage.md#contextinfo)

***

### inviteExpiration?

> `optional` **inviteExpiration**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:28543](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28543)

NewsletterAdminInviteMessage inviteExpiration.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`inviteExpiration`](../interfaces/INewsletterAdminInviteMessage.md#inviteexpiration)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:28537](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28537)

NewsletterAdminInviteMessage jpegThumbnail.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`jpegThumbnail`](../interfaces/INewsletterAdminInviteMessage.md#jpegthumbnail)

***

### newsletterJid?

> `optional` **newsletterJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28531](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28531)

NewsletterAdminInviteMessage newsletterJid.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`newsletterJid`](../interfaces/INewsletterAdminInviteMessage.md#newsletterjid)

***

### newsletterName?

> `optional` **newsletterName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28534](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28534)

NewsletterAdminInviteMessage newsletterName.

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`newsletterName`](../interfaces/INewsletterAdminInviteMessage.md#newslettername)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28616](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28616)

Converts this NewsletterAdminInviteMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:28553](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28553)

Creates a new NewsletterAdminInviteMessage instance using the specified properties.

#### Parameters

##### properties?

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

Properties to set

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:28579](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28579)

Decodes a NewsletterAdminInviteMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:28588](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28588)

Decodes a NewsletterAdminInviteMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28561](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28561)

Encodes the specified NewsletterAdminInviteMessage message. Does not implicitly [verify](NewsletterAdminInviteMessage.md#verify) messages.

#### Parameters

##### message

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28569](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28569)

Encodes the specified NewsletterAdminInviteMessage message, length delimited. Does not implicitly [verify](NewsletterAdminInviteMessage.md#verify) messages.

#### Parameters

##### message

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:28602](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28602)

Creates a NewsletterAdminInviteMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:28623](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28623)

Gets the default type url for NewsletterAdminInviteMessage

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

Defined in: [WAProto/index.d.ts:28610](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28610)

Creates a plain object from a NewsletterAdminInviteMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

NewsletterAdminInviteMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28595](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L28595)

Verifies a NewsletterAdminInviteMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
