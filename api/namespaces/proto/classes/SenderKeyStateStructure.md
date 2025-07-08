# Class: SenderKeyStateStructure

Defined in: [WAProto/index.d.ts:41271](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41271)

Represents a SenderKeyStateStructure.

## Implements

- [`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

## Constructors

### new SenderKeyStateStructure()

> **new SenderKeyStateStructure**(`properties`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:41277](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41277)

Constructs a new SenderKeyStateStructure.

#### Parameters

##### properties?

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

Properties to set

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

## Properties

### senderChainKey?

> `optional` **senderChainKey**: `null` \| [`ISenderChainKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderChainKey.md)

Defined in: [WAProto/index.d.ts:41283](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41283)

SenderKeyStateStructure senderChainKey.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderChainKey`](../interfaces/ISenderKeyStateStructure.md#senderchainkey)

***

### senderKeyId?

> `optional` **senderKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:41280](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41280)

SenderKeyStateStructure senderKeyId.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderKeyId`](../interfaces/ISenderKeyStateStructure.md#senderkeyid)

***

### senderMessageKeys

> **senderMessageKeys**: [`ISenderMessageKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderMessageKey.md)[]

Defined in: [WAProto/index.d.ts:41289](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41289)

SenderKeyStateStructure senderMessageKeys.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderMessageKeys`](../interfaces/ISenderKeyStateStructure.md#sendermessagekeys)

***

### senderSigningKey?

> `optional` **senderSigningKey**: `null` \| [`ISenderSigningKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderSigningKey.md)

Defined in: [WAProto/index.d.ts:41286](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41286)

SenderKeyStateStructure senderSigningKey.

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderSigningKey`](../interfaces/ISenderKeyStateStructure.md#sendersigningkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:41359](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41359)

Converts this SenderKeyStateStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:41296](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41296)

Creates a new SenderKeyStateStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

Properties to set

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:41322](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41322)

Decodes a SenderKeyStateStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:41331](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41331)

Decodes a SenderKeyStateStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41304](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41304)

Encodes the specified SenderKeyStateStructure message. Does not implicitly [verify](SenderKeyStateStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

SenderKeyStateStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41312](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41312)

Encodes the specified SenderKeyStateStructure message, length delimited. Does not implicitly [verify](SenderKeyStateStructure.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

SenderKeyStateStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:41345](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41345)

Creates a SenderKeyStateStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:41366](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41366)

Gets the default type url for SenderKeyStateStructure

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

Defined in: [WAProto/index.d.ts:41353](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41353)

Creates a plain object from a SenderKeyStateStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

SenderKeyStateStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:41338](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L41338)

Verifies a SenderKeyStateStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
