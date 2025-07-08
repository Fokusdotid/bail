# Class: NativeFlowButton

Defined in: [WAProto/index.d.ts:25773](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25773)

Represents a NativeFlowButton.

## Implements

- [`INativeFlowButton`](../interfaces/INativeFlowButton.md)

## Constructors

### new NativeFlowButton()

> **new NativeFlowButton**(`properties`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:25779](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25779)

Constructs a new NativeFlowButton.

#### Parameters

##### properties?

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

Properties to set

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

## Properties

### buttonParamsJson?

> `optional` **buttonParamsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25785](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25785)

NativeFlowButton buttonParamsJson.

#### Implementation of

[`INativeFlowButton`](../interfaces/INativeFlowButton.md).[`buttonParamsJson`](../interfaces/INativeFlowButton.md#buttonparamsjson)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25782](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25782)

NativeFlowButton name.

#### Implementation of

[`INativeFlowButton`](../interfaces/INativeFlowButton.md).[`name`](../interfaces/INativeFlowButton.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25855](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25855)

Converts this NativeFlowButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:25792](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25792)

Creates a new NativeFlowButton instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

Properties to set

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:25818](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25818)

Decodes a NativeFlowButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:25827](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25827)

Decodes a NativeFlowButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25800](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25800)

Encodes the specified NativeFlowButton message. Does not implicitly [verify](NativeFlowButton.md#verify) messages.

#### Parameters

##### message

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

NativeFlowButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25808](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25808)

Encodes the specified NativeFlowButton message, length delimited. Does not implicitly [verify](NativeFlowButton.md#verify) messages.

#### Parameters

##### message

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

NativeFlowButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:25841](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25841)

Creates a NativeFlowButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:25862](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25862)

Gets the default type url for NativeFlowButton

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

Defined in: [WAProto/index.d.ts:25849](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25849)

Creates a plain object from a NativeFlowButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowButton`](NativeFlowButton.md)

NativeFlowButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25834](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L25834)

Verifies a NativeFlowButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
