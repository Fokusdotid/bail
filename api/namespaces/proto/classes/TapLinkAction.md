# Class: TapLinkAction

Defined in: [WAProto/index.d.ts:50737](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50737)

Represents a TapLinkAction.

## Implements

- [`ITapLinkAction`](../interfaces/ITapLinkAction.md)

## Constructors

### new TapLinkAction()

> **new TapLinkAction**(`properties`?): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:50743](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50743)

Constructs a new TapLinkAction.

#### Parameters

##### properties?

[`ITapLinkAction`](../interfaces/ITapLinkAction.md)

Properties to set

#### Returns

[`TapLinkAction`](TapLinkAction.md)

## Properties

### tapUrl?

> `optional` **tapUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:50749](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50749)

TapLinkAction tapUrl.

#### Implementation of

[`ITapLinkAction`](../interfaces/ITapLinkAction.md).[`tapUrl`](../interfaces/ITapLinkAction.md#tapurl)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:50746](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50746)

TapLinkAction title.

#### Implementation of

[`ITapLinkAction`](../interfaces/ITapLinkAction.md).[`title`](../interfaces/ITapLinkAction.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50819](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50819)

Converts this TapLinkAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:50756](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50756)

Creates a new TapLinkAction instance using the specified properties.

#### Parameters

##### properties?

[`ITapLinkAction`](../interfaces/ITapLinkAction.md)

Properties to set

#### Returns

[`TapLinkAction`](TapLinkAction.md)

TapLinkAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:50782](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50782)

Decodes a TapLinkAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TapLinkAction`](TapLinkAction.md)

TapLinkAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:50791](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50791)

Decodes a TapLinkAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TapLinkAction`](TapLinkAction.md)

TapLinkAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50764](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50764)

Encodes the specified TapLinkAction message. Does not implicitly [verify](TapLinkAction.md#verify) messages.

#### Parameters

##### message

[`ITapLinkAction`](../interfaces/ITapLinkAction.md)

TapLinkAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50772](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50772)

Encodes the specified TapLinkAction message, length delimited. Does not implicitly [verify](TapLinkAction.md#verify) messages.

#### Parameters

##### message

[`ITapLinkAction`](../interfaces/ITapLinkAction.md)

TapLinkAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:50805](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50805)

Creates a TapLinkAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TapLinkAction`](TapLinkAction.md)

TapLinkAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50826](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50826)

Gets the default type url for TapLinkAction

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

Defined in: [WAProto/index.d.ts:50813](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50813)

Creates a plain object from a TapLinkAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`TapLinkAction`](TapLinkAction.md)

TapLinkAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50798](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L50798)

Verifies a TapLinkAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
