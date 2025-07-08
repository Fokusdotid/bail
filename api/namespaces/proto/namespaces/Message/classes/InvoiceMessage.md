# Class: InvoiceMessage

Defined in: [WAProto/index.d.ts:26358](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26358)

Represents an InvoiceMessage.

## Implements

- [`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

## Constructors

### new InvoiceMessage()

> **new InvoiceMessage**(`properties`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:26364](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26364)

Constructs a new InvoiceMessage.

#### Parameters

##### properties?

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

Properties to set

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

## Properties

### attachmentDirectPath?

> `optional` **attachmentDirectPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26391](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26391)

InvoiceMessage attachmentDirectPath.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentDirectPath`](../interfaces/IInvoiceMessage.md#attachmentdirectpath)

***

### attachmentFileEncSha256?

> `optional` **attachmentFileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:26388](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26388)

InvoiceMessage attachmentFileEncSha256.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentFileEncSha256`](../interfaces/IInvoiceMessage.md#attachmentfileencsha256)

***

### attachmentFileSha256?

> `optional` **attachmentFileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:26385](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26385)

InvoiceMessage attachmentFileSha256.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentFileSha256`](../interfaces/IInvoiceMessage.md#attachmentfilesha256)

***

### attachmentJpegThumbnail?

> `optional` **attachmentJpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:26394](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26394)

InvoiceMessage attachmentJpegThumbnail.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentJpegThumbnail`](../interfaces/IInvoiceMessage.md#attachmentjpegthumbnail)

***

### attachmentMediaKey?

> `optional` **attachmentMediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:26379](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26379)

InvoiceMessage attachmentMediaKey.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMediaKey`](../interfaces/IInvoiceMessage.md#attachmentmediakey)

***

### attachmentMediaKeyTimestamp?

> `optional` **attachmentMediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:26382](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26382)

InvoiceMessage attachmentMediaKeyTimestamp.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMediaKeyTimestamp`](../interfaces/IInvoiceMessage.md#attachmentmediakeytimestamp)

***

### attachmentMimetype?

> `optional` **attachmentMimetype**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26376](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26376)

InvoiceMessage attachmentMimetype.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMimetype`](../interfaces/IInvoiceMessage.md#attachmentmimetype)

***

### attachmentType?

> `optional` **attachmentType**: `null` \| [`AttachmentType`](../namespaces/InvoiceMessage/enumerations/AttachmentType.md)

Defined in: [WAProto/index.d.ts:26373](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26373)

InvoiceMessage attachmentType.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentType`](../interfaces/IInvoiceMessage.md#attachmenttype)

***

### note?

> `optional` **note**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26367](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26367)

InvoiceMessage note.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`note`](../interfaces/IInvoiceMessage.md#note)

***

### token?

> `optional` **token**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26370](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26370)

InvoiceMessage token.

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`token`](../interfaces/IInvoiceMessage.md#token)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26464](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26464)

Converts this InvoiceMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:26401](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26401)

Creates a new InvoiceMessage instance using the specified properties.

#### Parameters

##### properties?

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

Properties to set

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:26427](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26427)

Decodes an InvoiceMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:26436](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26436)

Decodes an InvoiceMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26409](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26409)

Encodes the specified InvoiceMessage message. Does not implicitly [verify](InvoiceMessage.md#verify) messages.

#### Parameters

##### message

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

InvoiceMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26417](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26417)

Encodes the specified InvoiceMessage message, length delimited. Does not implicitly [verify](InvoiceMessage.md#verify) messages.

#### Parameters

##### message

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

InvoiceMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:26450](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26450)

Creates an InvoiceMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:26471](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26471)

Gets the default type url for InvoiceMessage

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

Defined in: [WAProto/index.d.ts:26458](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26458)

Creates a plain object from an InvoiceMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`InvoiceMessage`](InvoiceMessage.md)

InvoiceMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26443](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L26443)

Verifies an InvoiceMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
