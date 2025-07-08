# Class: AdReplyInfo

Defined in: [WAProto/index.d.ts:11129](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11129)

Represents an AdReplyInfo.

## Implements

- [`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

## Constructors

### new AdReplyInfo()

> **new AdReplyInfo**(`properties`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:11135](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11135)

Constructs a new AdReplyInfo.

#### Parameters

##### properties?

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

Properties to set

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

## Properties

### advertiserName?

> `optional` **advertiserName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11138](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11138)

AdReplyInfo advertiserName.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`advertiserName`](../interfaces/IAdReplyInfo.md#advertisername)

***

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11147](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11147)

AdReplyInfo caption.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`caption`](../interfaces/IAdReplyInfo.md#caption)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11144](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11144)

AdReplyInfo jpegThumbnail.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`jpegThumbnail`](../interfaces/IAdReplyInfo.md#jpegthumbnail)

***

### mediaType?

> `optional` **mediaType**: `null` \| [`MediaType`](../namespaces/AdReplyInfo/enumerations/MediaType.md)

Defined in: [WAProto/index.d.ts:11141](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11141)

AdReplyInfo mediaType.

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`mediaType`](../interfaces/IAdReplyInfo.md#mediatype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11217](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11217)

Converts this AdReplyInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:11154](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11154)

Creates a new AdReplyInfo instance using the specified properties.

#### Parameters

##### properties?

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

Properties to set

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:11180](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11180)

Decodes an AdReplyInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:11189](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11189)

Decodes an AdReplyInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11162](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11162)

Encodes the specified AdReplyInfo message. Does not implicitly [verify](AdReplyInfo.md#verify) messages.

#### Parameters

##### message

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

AdReplyInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11170](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11170)

Encodes the specified AdReplyInfo message, length delimited. Does not implicitly [verify](AdReplyInfo.md#verify) messages.

#### Parameters

##### message

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

AdReplyInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:11203](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11203)

Creates an AdReplyInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11224](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11224)

Gets the default type url for AdReplyInfo

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

Defined in: [WAProto/index.d.ts:11211](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11211)

Creates a plain object from an AdReplyInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`AdReplyInfo`](AdReplyInfo.md)

AdReplyInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:11196](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L11196)

Verifies an AdReplyInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
