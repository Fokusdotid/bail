# Class: NativeFlowMessage

Defined in: [WAProto/index.d.ts:25665](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25665)

Represents a NativeFlowMessage.

## Implements

- [`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

## Constructors

### new NativeFlowMessage()

> **new NativeFlowMessage**(`properties`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:25671](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25671)

Constructs a new NativeFlowMessage.

#### Parameters

##### properties?

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

Properties to set

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

## Properties

### buttons

> **buttons**: [`INativeFlowButton`](../namespaces/NativeFlowMessage/interfaces/INativeFlowButton.md)[]

Defined in: [WAProto/index.d.ts:25674](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25674)

NativeFlowMessage buttons.

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`buttons`](../interfaces/INativeFlowMessage.md#buttons)

***

### messageParamsJson?

> `optional` **messageParamsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25677](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25677)

NativeFlowMessage messageParamsJson.

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`messageParamsJson`](../interfaces/INativeFlowMessage.md#messageparamsjson)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:25680](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25680)

NativeFlowMessage messageVersion.

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`messageVersion`](../interfaces/INativeFlowMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25750](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25750)

Converts this NativeFlowMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:25687](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25687)

Creates a new NativeFlowMessage instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

Properties to set

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:25713](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25713)

Decodes a NativeFlowMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:25722](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25722)

Decodes a NativeFlowMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25695](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25695)

Encodes the specified NativeFlowMessage message. Does not implicitly [verify](NativeFlowMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

NativeFlowMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25703](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25703)

Encodes the specified NativeFlowMessage message, length delimited. Does not implicitly [verify](NativeFlowMessage.md#verify) messages.

#### Parameters

##### message

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

NativeFlowMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:25736](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25736)

Creates a NativeFlowMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:25757](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25757)

Gets the default type url for NativeFlowMessage

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

Defined in: [WAProto/index.d.ts:25744](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25744)

Creates a plain object from a NativeFlowMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowMessage`](NativeFlowMessage.md)

NativeFlowMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25729](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L25729)

Verifies a NativeFlowMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
