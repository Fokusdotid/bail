# Class: EncReactionMessage

Defined in: [WAProto/index.d.ts:22659](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22659)

Represents an EncReactionMessage.

## Implements

- [`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

## Constructors

### new EncReactionMessage()

> **new EncReactionMessage**(`properties`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:22665](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22665)

Constructs a new EncReactionMessage.

#### Parameters

##### properties?

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

Properties to set

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:22674](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22674)

EncReactionMessage encIv.

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`encIv`](../interfaces/IEncReactionMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:22671](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22671)

EncReactionMessage encPayload.

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`encPayload`](../interfaces/IEncReactionMessage.md#encpayload)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:22668](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22668)

EncReactionMessage targetMessageKey.

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`targetMessageKey`](../interfaces/IEncReactionMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22744](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22744)

Converts this EncReactionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:22681](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22681)

Creates a new EncReactionMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

Properties to set

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:22707](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22707)

Decodes an EncReactionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:22716](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22716)

Decodes an EncReactionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22689](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22689)

Encodes the specified EncReactionMessage message. Does not implicitly [verify](EncReactionMessage.md#verify) messages.

#### Parameters

##### message

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

EncReactionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22697](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22697)

Encodes the specified EncReactionMessage message, length delimited. Does not implicitly [verify](EncReactionMessage.md#verify) messages.

#### Parameters

##### message

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

EncReactionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:22730](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22730)

Creates an EncReactionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:22751](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22751)

Gets the default type url for EncReactionMessage

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

Defined in: [WAProto/index.d.ts:22738](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22738)

Creates a plain object from an EncReactionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EncReactionMessage`](EncReactionMessage.md)

EncReactionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22723](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L22723)

Verifies an EncReactionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
