# Class: ClientFinish

Defined in: [WAProto/index.d.ts:15451](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15451)

Represents a ClientFinish.

## Implements

- [`IClientFinish`](../interfaces/IClientFinish.md)

## Constructors

### new ClientFinish()

> **new ClientFinish**(`properties`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:15457](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15457)

Constructs a new ClientFinish.

#### Parameters

##### properties?

[`IClientFinish`](../interfaces/IClientFinish.md)

Properties to set

#### Returns

[`ClientFinish`](ClientFinish.md)

## Properties

### payload?

> `optional` **payload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15463](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15463)

ClientFinish payload.

#### Implementation of

[`IClientFinish`](../interfaces/IClientFinish.md).[`payload`](../interfaces/IClientFinish.md#payload)

***

### static?

> `optional` **static**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15460](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15460)

ClientFinish static.

#### Implementation of

[`IClientFinish`](../interfaces/IClientFinish.md).[`static`](../interfaces/IClientFinish.md#static)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15533](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15533)

Converts this ClientFinish to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:15470](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15470)

Creates a new ClientFinish instance using the specified properties.

#### Parameters

##### properties?

[`IClientFinish`](../interfaces/IClientFinish.md)

Properties to set

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:15496](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15496)

Decodes a ClientFinish message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:15505](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15505)

Decodes a ClientFinish message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15478](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15478)

Encodes the specified ClientFinish message. Does not implicitly [verify](ClientFinish.md#verify) messages.

#### Parameters

##### message

[`IClientFinish`](../interfaces/IClientFinish.md)

ClientFinish message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15486](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15486)

Encodes the specified ClientFinish message, length delimited. Does not implicitly [verify](ClientFinish.md#verify) messages.

#### Parameters

##### message

[`IClientFinish`](../interfaces/IClientFinish.md)

ClientFinish message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:15519](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15519)

Creates a ClientFinish message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ClientFinish`](ClientFinish.md)

ClientFinish

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:15540](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15540)

Gets the default type url for ClientFinish

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

Defined in: [WAProto/index.d.ts:15527](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15527)

Creates a plain object from a ClientFinish message. Also converts values to other types if specified.

#### Parameters

##### message

[`ClientFinish`](ClientFinish.md)

ClientFinish

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15512](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L15512)

Verifies a ClientFinish message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
