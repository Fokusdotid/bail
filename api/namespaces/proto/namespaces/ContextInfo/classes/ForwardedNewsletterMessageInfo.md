# Class: ForwardedNewsletterMessageInfo

Defined in: [WAProto/index.d.ts:12068](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12068)

Represents a ForwardedNewsletterMessageInfo.

## Implements

- [`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

## Constructors

### new ForwardedNewsletterMessageInfo()

> **new ForwardedNewsletterMessageInfo**(`properties`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:12074](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12074)

Constructs a new ForwardedNewsletterMessageInfo.

#### Parameters

##### properties?

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

Properties to set

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

## Properties

### accessibilityText?

> `optional` **accessibilityText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12089](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12089)

ForwardedNewsletterMessageInfo accessibilityText.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`accessibilityText`](../interfaces/IForwardedNewsletterMessageInfo.md#accessibilitytext)

***

### contentType?

> `optional` **contentType**: `null` \| [`ContentType`](../namespaces/ForwardedNewsletterMessageInfo/enumerations/ContentType.md)

Defined in: [WAProto/index.d.ts:12086](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12086)

ForwardedNewsletterMessageInfo contentType.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`contentType`](../interfaces/IForwardedNewsletterMessageInfo.md#contenttype)

***

### newsletterJid?

> `optional` **newsletterJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12077](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12077)

ForwardedNewsletterMessageInfo newsletterJid.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`newsletterJid`](../interfaces/IForwardedNewsletterMessageInfo.md#newsletterjid)

***

### newsletterName?

> `optional` **newsletterName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12083](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12083)

ForwardedNewsletterMessageInfo newsletterName.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`newsletterName`](../interfaces/IForwardedNewsletterMessageInfo.md#newslettername)

***

### serverMessageId?

> `optional` **serverMessageId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12080](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12080)

ForwardedNewsletterMessageInfo serverMessageId.

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`serverMessageId`](../interfaces/IForwardedNewsletterMessageInfo.md#servermessageid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12159](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12159)

Converts this ForwardedNewsletterMessageInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:12096](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12096)

Creates a new ForwardedNewsletterMessageInfo instance using the specified properties.

#### Parameters

##### properties?

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

Properties to set

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:12122](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12122)

Decodes a ForwardedNewsletterMessageInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:12131](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12131)

Decodes a ForwardedNewsletterMessageInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12104](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12104)

Encodes the specified ForwardedNewsletterMessageInfo message. Does not implicitly [verify](ForwardedNewsletterMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12112](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12112)

Encodes the specified ForwardedNewsletterMessageInfo message, length delimited. Does not implicitly [verify](ForwardedNewsletterMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:12145](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12145)

Creates a ForwardedNewsletterMessageInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12166](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12166)

Gets the default type url for ForwardedNewsletterMessageInfo

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

Defined in: [WAProto/index.d.ts:12153](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12153)

Creates a plain object from a ForwardedNewsletterMessageInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

ForwardedNewsletterMessageInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12138](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12138)

Verifies a ForwardedNewsletterMessageInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
