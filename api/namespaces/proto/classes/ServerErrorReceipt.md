# Class: ServerErrorReceipt

Defined in: [WAProto/index.d.ts:41689](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41689)

Represents a ServerErrorReceipt.

## Implements

- [`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

## Constructors

### new ServerErrorReceipt()

> **new ServerErrorReceipt**(`properties`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:41695](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41695)

Constructs a new ServerErrorReceipt.

#### Parameters

##### properties?

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

Properties to set

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

## Properties

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:41698](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41698)

ServerErrorReceipt stanzaId.

#### Implementation of

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md).[`stanzaId`](../interfaces/IServerErrorReceipt.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:41768](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41768)

Converts this ServerErrorReceipt to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:41705](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41705)

Creates a new ServerErrorReceipt instance using the specified properties.

#### Parameters

##### properties?

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

Properties to set

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:41731](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41731)

Decodes a ServerErrorReceipt message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:41740](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41740)

Decodes a ServerErrorReceipt message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41713](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41713)

Encodes the specified ServerErrorReceipt message. Does not implicitly [verify](ServerErrorReceipt.md#verify) messages.

#### Parameters

##### message

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

ServerErrorReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41721](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41721)

Encodes the specified ServerErrorReceipt message, length delimited. Does not implicitly [verify](ServerErrorReceipt.md#verify) messages.

#### Parameters

##### message

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

ServerErrorReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:41754](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41754)

Creates a ServerErrorReceipt message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:41775](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41775)

Gets the default type url for ServerErrorReceipt

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

Defined in: [WAProto/index.d.ts:41762](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41762)

Creates a plain object from a ServerErrorReceipt message. Also converts values to other types if specified.

#### Parameters

##### message

[`ServerErrorReceipt`](ServerErrorReceipt.md)

ServerErrorReceipt

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:41747](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L41747)

Verifies a ServerErrorReceipt message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
