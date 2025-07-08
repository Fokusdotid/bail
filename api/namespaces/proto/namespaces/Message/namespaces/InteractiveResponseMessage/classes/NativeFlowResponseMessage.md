# Class: NativeFlowResponseMessage

Defined in: [WAProto/index.d.ts:26227](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26227)

Represents a NativeFlowResponseMessage.

## Implements

- [`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

## Constructors

### new NativeFlowResponseMessage()

> **new NativeFlowResponseMessage**(`properties`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:26233](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26233)

Constructs a new NativeFlowResponseMessage.

#### Parameters

##### properties?

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

Properties to set

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

## Properties

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26236](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26236)

NativeFlowResponseMessage name.

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`name`](../interfaces/INativeFlowResponseMessage.md#name)

***

### paramsJson?

> `optional` **paramsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:26239](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26239)

NativeFlowResponseMessage paramsJson.

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`paramsJson`](../interfaces/INativeFlowResponseMessage.md#paramsjson)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:26242](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26242)

NativeFlowResponseMessage version.

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`version`](../interfaces/INativeFlowResponseMessage.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26312](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26312)

Converts this NativeFlowResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:26249](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26249)

Creates a new NativeFlowResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

Properties to set

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:26275](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26275)

Decodes a NativeFlowResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:26284](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26284)

Decodes a NativeFlowResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26257](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26257)

Encodes the specified NativeFlowResponseMessage message. Does not implicitly [verify](NativeFlowResponseMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

NativeFlowResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26265](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26265)

Encodes the specified NativeFlowResponseMessage message, length delimited. Does not implicitly [verify](NativeFlowResponseMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

NativeFlowResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:26298](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26298)

Creates a NativeFlowResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:26319](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26319)

Gets the default type url for NativeFlowResponseMessage

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

Defined in: [WAProto/index.d.ts:26306](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26306)

Creates a plain object from a NativeFlowResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

NativeFlowResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26291](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L26291)

Verifies a NativeFlowResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
