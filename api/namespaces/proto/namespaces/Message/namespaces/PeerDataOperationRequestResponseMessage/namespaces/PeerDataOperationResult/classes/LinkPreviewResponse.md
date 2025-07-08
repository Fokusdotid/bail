# Class: LinkPreviewResponse

Defined in: [WAProto/index.d.ts:30500](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30500)

Represents a LinkPreviewResponse.

## Implements

- [`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

## Constructors

### new LinkPreviewResponse()

> **new LinkPreviewResponse**(`properties`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:30506](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30506)

Constructs a new LinkPreviewResponse.

#### Parameters

##### properties?

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

Properties to set

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

## Properties

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30515](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30515)

LinkPreviewResponse description.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`description`](../interfaces/ILinkPreviewResponse.md#description)

***

### hqThumbnail?

> `optional` **hqThumbnail**: `null` \| [`ILinkPreviewHighQualityThumbnail`](../namespaces/LinkPreviewResponse/interfaces/ILinkPreviewHighQualityThumbnail.md)

Defined in: [WAProto/index.d.ts:30527](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30527)

LinkPreviewResponse hqThumbnail.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`hqThumbnail`](../interfaces/ILinkPreviewResponse.md#hqthumbnail)

***

### matchText?

> `optional` **matchText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30521](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30521)

LinkPreviewResponse matchText.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`matchText`](../interfaces/ILinkPreviewResponse.md#matchtext)

***

### previewType?

> `optional` **previewType**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30524](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30524)

LinkPreviewResponse previewType.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`previewType`](../interfaces/ILinkPreviewResponse.md#previewtype)

***

### thumbData?

> `optional` **thumbData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:30518](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30518)

LinkPreviewResponse thumbData.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`thumbData`](../interfaces/ILinkPreviewResponse.md#thumbdata)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30512](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30512)

LinkPreviewResponse title.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`title`](../interfaces/ILinkPreviewResponse.md#title)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30509](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30509)

LinkPreviewResponse url.

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`url`](../interfaces/ILinkPreviewResponse.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30597](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30597)

Converts this LinkPreviewResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:30534](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30534)

Creates a new LinkPreviewResponse instance using the specified properties.

#### Parameters

##### properties?

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

Properties to set

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:30560](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30560)

Decodes a LinkPreviewResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:30569](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30569)

Decodes a LinkPreviewResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30542](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30542)

Encodes the specified LinkPreviewResponse message. Does not implicitly [verify](LinkPreviewResponse.md#verify) messages.

#### Parameters

##### message

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

LinkPreviewResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30550](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30550)

Encodes the specified LinkPreviewResponse message, length delimited. Does not implicitly [verify](LinkPreviewResponse.md#verify) messages.

#### Parameters

##### message

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

LinkPreviewResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:30583](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30583)

Creates a LinkPreviewResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:30604](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30604)

Gets the default type url for LinkPreviewResponse

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

Defined in: [WAProto/index.d.ts:30591](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30591)

Creates a plain object from a LinkPreviewResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`LinkPreviewResponse`](LinkPreviewResponse.md)

LinkPreviewResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30576](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L30576)

Verifies a LinkPreviewResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
