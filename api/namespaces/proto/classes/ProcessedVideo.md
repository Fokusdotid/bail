# Class: ProcessedVideo

Defined in: [WAProto/index.d.ts:40067](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40067)

Represents a ProcessedVideo.

## Implements

- [`IProcessedVideo`](../interfaces/IProcessedVideo.md)

## Constructors

### new ProcessedVideo()

> **new ProcessedVideo**(`properties`?): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:40073](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40073)

Constructs a new ProcessedVideo.

#### Parameters

##### properties?

[`IProcessedVideo`](../interfaces/IProcessedVideo.md)

Properties to set

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

## Properties

### bitrate?

> `optional` **bitrate**: `null` \| `number`

Defined in: [WAProto/index.d.ts:40091](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40091)

ProcessedVideo bitrate.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`bitrate`](../interfaces/IProcessedVideo.md#bitrate)

***

### capabilities

> **capabilities**: `string`[]

Defined in: [WAProto/index.d.ts:40097](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40097)

ProcessedVideo capabilities.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`capabilities`](../interfaces/IProcessedVideo.md#capabilities)

***

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:40076](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40076)

ProcessedVideo directPath.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`directPath`](../interfaces/IProcessedVideo.md#directpath)

***

### fileLength?

> `optional` **fileLength**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:40088](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40088)

ProcessedVideo fileLength.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`fileLength`](../interfaces/IProcessedVideo.md#filelength)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:40079](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40079)

ProcessedVideo fileSha256.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`fileSha256`](../interfaces/IProcessedVideo.md#filesha256)

***

### height?

> `optional` **height**: `null` \| `number`

Defined in: [WAProto/index.d.ts:40082](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40082)

ProcessedVideo height.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`height`](../interfaces/IProcessedVideo.md#height)

***

### quality?

> `optional` **quality**: `null` \| [`VideoQuality`](../namespaces/ProcessedVideo/enumerations/VideoQuality.md)

Defined in: [WAProto/index.d.ts:40094](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40094)

ProcessedVideo quality.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`quality`](../interfaces/IProcessedVideo.md#quality)

***

### width?

> `optional` **width**: `null` \| `number`

Defined in: [WAProto/index.d.ts:40085](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40085)

ProcessedVideo width.

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`width`](../interfaces/IProcessedVideo.md#width)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:40167](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40167)

Converts this ProcessedVideo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:40104](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40104)

Creates a new ProcessedVideo instance using the specified properties.

#### Parameters

##### properties?

[`IProcessedVideo`](../interfaces/IProcessedVideo.md)

Properties to set

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

ProcessedVideo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:40130](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40130)

Decodes a ProcessedVideo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

ProcessedVideo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:40139](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40139)

Decodes a ProcessedVideo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

ProcessedVideo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40112](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40112)

Encodes the specified ProcessedVideo message. Does not implicitly [verify](ProcessedVideo.md#verify) messages.

#### Parameters

##### message

[`IProcessedVideo`](../interfaces/IProcessedVideo.md)

ProcessedVideo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40120](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40120)

Encodes the specified ProcessedVideo message, length delimited. Does not implicitly [verify](ProcessedVideo.md#verify) messages.

#### Parameters

##### message

[`IProcessedVideo`](../interfaces/IProcessedVideo.md)

ProcessedVideo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:40153](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40153)

Creates a ProcessedVideo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

ProcessedVideo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:40174](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40174)

Gets the default type url for ProcessedVideo

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

Defined in: [WAProto/index.d.ts:40161](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40161)

Creates a plain object from a ProcessedVideo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProcessedVideo`](ProcessedVideo.md)

ProcessedVideo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:40146](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L40146)

Verifies a ProcessedVideo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
