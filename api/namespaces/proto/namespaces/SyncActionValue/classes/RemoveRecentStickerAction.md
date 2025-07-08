# Class: RemoveRecentStickerAction

Defined in: [WAProto/index.d.ts:48383](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48383)

Represents a RemoveRecentStickerAction.

## Implements

- [`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

## Constructors

### new RemoveRecentStickerAction()

> **new RemoveRecentStickerAction**(`properties`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:48389](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48389)

Constructs a new RemoveRecentStickerAction.

#### Parameters

##### properties?

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

Properties to set

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

## Properties

### lastStickerSentTs?

> `optional` **lastStickerSentTs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:48392](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48392)

RemoveRecentStickerAction lastStickerSentTs.

#### Implementation of

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md).[`lastStickerSentTs`](../interfaces/IRemoveRecentStickerAction.md#laststickersentts)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48462](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48462)

Converts this RemoveRecentStickerAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:48399](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48399)

Creates a new RemoveRecentStickerAction instance using the specified properties.

#### Parameters

##### properties?

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

Properties to set

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:48425](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48425)

Decodes a RemoveRecentStickerAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:48434](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48434)

Decodes a RemoveRecentStickerAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48407](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48407)

Encodes the specified RemoveRecentStickerAction message. Does not implicitly [verify](RemoveRecentStickerAction.md#verify) messages.

#### Parameters

##### message

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

RemoveRecentStickerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48415](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48415)

Encodes the specified RemoveRecentStickerAction message, length delimited. Does not implicitly [verify](RemoveRecentStickerAction.md#verify) messages.

#### Parameters

##### message

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

RemoveRecentStickerAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:48448](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48448)

Creates a RemoveRecentStickerAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48469](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48469)

Gets the default type url for RemoveRecentStickerAction

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

Defined in: [WAProto/index.d.ts:48456](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48456)

Creates a plain object from a RemoveRecentStickerAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

RemoveRecentStickerAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48441](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L48441)

Verifies a RemoveRecentStickerAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
