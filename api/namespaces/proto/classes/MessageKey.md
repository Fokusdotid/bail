# Class: MessageKey

Defined in: [WAProto/index.d.ts:36149](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36149)

Represents a MessageKey.

## Implements

- [`IMessageKey`](../interfaces/IMessageKey.md)

## Constructors

### new MessageKey()

> **new MessageKey**(`properties`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:36155](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36155)

Constructs a new MessageKey.

#### Parameters

##### properties?

[`IMessageKey`](../interfaces/IMessageKey.md)

Properties to set

#### Returns

[`MessageKey`](MessageKey.md)

## Properties

### fromMe?

> `optional` **fromMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:36161](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36161)

MessageKey fromMe.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`fromMe`](../interfaces/IMessageKey.md#fromme)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:36164](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36164)

MessageKey id.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`id`](../interfaces/IMessageKey.md#id)

***

### participant?

> `optional` **participant**: `null` \| `string`

Defined in: [WAProto/index.d.ts:36167](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36167)

MessageKey participant.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`participant`](../interfaces/IMessageKey.md#participant)

***

### remoteJid?

> `optional` **remoteJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:36158](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36158)

MessageKey remoteJid.

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`remoteJid`](../interfaces/IMessageKey.md#remotejid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:36237](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36237)

Converts this MessageKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:36174](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36174)

Creates a new MessageKey instance using the specified properties.

#### Parameters

##### properties?

[`IMessageKey`](../interfaces/IMessageKey.md)

Properties to set

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:36200](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36200)

Decodes a MessageKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:36209](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36209)

Decodes a MessageKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36182](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36182)

Encodes the specified MessageKey message. Does not implicitly [verify](MessageKey.md#verify) messages.

#### Parameters

##### message

[`IMessageKey`](../interfaces/IMessageKey.md)

MessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36190](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36190)

Encodes the specified MessageKey message, length delimited. Does not implicitly [verify](MessageKey.md#verify) messages.

#### Parameters

##### message

[`IMessageKey`](../interfaces/IMessageKey.md)

MessageKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:36223](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36223)

Creates a MessageKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageKey`](MessageKey.md)

MessageKey

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:36244](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36244)

Gets the default type url for MessageKey

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

Defined in: [WAProto/index.d.ts:36231](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36231)

Creates a plain object from a MessageKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageKey`](MessageKey.md)

MessageKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:36216](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L36216)

Verifies a MessageKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
