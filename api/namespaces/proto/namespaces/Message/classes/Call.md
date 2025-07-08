# Class: Call

Defined in: [WAProto/index.d.ts:20896](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20896)

Represents a Call.

## Implements

- [`ICall`](../interfaces/ICall.md)

## Constructors

### new Call()

> **new Call**(`properties`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:20902](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20902)

Constructs a new Call.

#### Parameters

##### properties?

[`ICall`](../interfaces/ICall.md)

Properties to set

#### Returns

[`Call`](Call.md)

## Properties

### callKey?

> `optional` **callKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:20905](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20905)

Call callKey.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`callKey`](../interfaces/ICall.md#callkey)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:20923](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20923)

Call contextInfo.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`contextInfo`](../interfaces/ICall.md#contextinfo)

***

### conversionData?

> `optional` **conversionData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:20911](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20911)

Call conversionData.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionData`](../interfaces/ICall.md#conversiondata)

***

### conversionDelaySeconds?

> `optional` **conversionDelaySeconds**: `null` \| `number`

Defined in: [WAProto/index.d.ts:20914](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20914)

Call conversionDelaySeconds.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionDelaySeconds`](../interfaces/ICall.md#conversiondelayseconds)

***

### conversionSource?

> `optional` **conversionSource**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20908](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20908)

Call conversionSource.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionSource`](../interfaces/ICall.md#conversionsource)

***

### ctwaPayload?

> `optional` **ctwaPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:20920](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20920)

Call ctwaPayload.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`ctwaPayload`](../interfaces/ICall.md#ctwapayload)

***

### ctwaSignals?

> `optional` **ctwaSignals**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20917](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20917)

Call ctwaSignals.

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`ctwaSignals`](../interfaces/ICall.md#ctwasignals)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20993](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20993)

Converts this Call to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:20930](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20930)

Creates a new Call instance using the specified properties.

#### Parameters

##### properties?

[`ICall`](../interfaces/ICall.md)

Properties to set

#### Returns

[`Call`](Call.md)

Call instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:20956](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20956)

Decodes a Call message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Call`](Call.md)

Call

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:20965](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20965)

Decodes a Call message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Call`](Call.md)

Call

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20938](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20938)

Encodes the specified Call message. Does not implicitly [verify](Call.md#verify) messages.

#### Parameters

##### message

[`ICall`](../interfaces/ICall.md)

Call message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20946](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20946)

Encodes the specified Call message, length delimited. Does not implicitly [verify](Call.md#verify) messages.

#### Parameters

##### message

[`ICall`](../interfaces/ICall.md)

Call message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:20979](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20979)

Creates a Call message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Call`](Call.md)

Call

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21000](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L21000)

Gets the default type url for Call

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

Defined in: [WAProto/index.d.ts:20987](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20987)

Creates a plain object from a Call message. Also converts values to other types if specified.

#### Parameters

##### message

[`Call`](Call.md)

Call

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20972](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L20972)

Verifies a Call message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
