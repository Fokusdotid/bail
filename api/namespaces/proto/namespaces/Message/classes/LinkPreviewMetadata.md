# Class: LinkPreviewMetadata

Defined in: [WAProto/index.d.ts:26606](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26606)

Represents a LinkPreviewMetadata.

## Implements

- [`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md)

## Constructors

### new LinkPreviewMetadata()

> **new LinkPreviewMetadata**(`properties`?): [`LinkPreviewMetadata`](LinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:26612](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26612)

Constructs a new LinkPreviewMetadata.

#### Parameters

##### properties?

[`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md)

Properties to set

#### Returns

[`LinkPreviewMetadata`](LinkPreviewMetadata.md)

## Properties

### fbExperimentId?

> `optional` **fbExperimentId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:26621](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26621)

LinkPreviewMetadata fbExperimentId.

#### Implementation of

[`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md).[`fbExperimentId`](../interfaces/ILinkPreviewMetadata.md#fbexperimentid)

***

### paymentLinkMetadata?

> `optional` **paymentLinkMetadata**: `null` \| [`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:26615](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26615)

LinkPreviewMetadata paymentLinkMetadata.

#### Implementation of

[`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md).[`paymentLinkMetadata`](../interfaces/ILinkPreviewMetadata.md#paymentlinkmetadata)

***

### urlMetadata?

> `optional` **urlMetadata**: `null` \| [`IURLMetadata`](../interfaces/IURLMetadata.md)

Defined in: [WAProto/index.d.ts:26618](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26618)

LinkPreviewMetadata urlMetadata.

#### Implementation of

[`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md).[`urlMetadata`](../interfaces/ILinkPreviewMetadata.md#urlmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26691](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26691)

Converts this LinkPreviewMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LinkPreviewMetadata`](LinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:26628](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26628)

Creates a new LinkPreviewMetadata instance using the specified properties.

#### Parameters

##### properties?

[`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md)

Properties to set

#### Returns

[`LinkPreviewMetadata`](LinkPreviewMetadata.md)

LinkPreviewMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LinkPreviewMetadata`](LinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:26654](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26654)

Decodes a LinkPreviewMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LinkPreviewMetadata`](LinkPreviewMetadata.md)

LinkPreviewMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LinkPreviewMetadata`](LinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:26663](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26663)

Decodes a LinkPreviewMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LinkPreviewMetadata`](LinkPreviewMetadata.md)

LinkPreviewMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26636](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26636)

Encodes the specified LinkPreviewMetadata message. Does not implicitly [verify](LinkPreviewMetadata.md#verify) messages.

#### Parameters

##### message

[`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md)

LinkPreviewMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26644](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26644)

Encodes the specified LinkPreviewMetadata message, length delimited. Does not implicitly [verify](LinkPreviewMetadata.md#verify) messages.

#### Parameters

##### message

[`ILinkPreviewMetadata`](../interfaces/ILinkPreviewMetadata.md)

LinkPreviewMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LinkPreviewMetadata`](LinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:26677](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26677)

Creates a LinkPreviewMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LinkPreviewMetadata`](LinkPreviewMetadata.md)

LinkPreviewMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:26698](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26698)

Gets the default type url for LinkPreviewMetadata

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

Defined in: [WAProto/index.d.ts:26685](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26685)

Creates a plain object from a LinkPreviewMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`LinkPreviewMetadata`](LinkPreviewMetadata.md)

LinkPreviewMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26670](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26670)

Verifies a LinkPreviewMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
