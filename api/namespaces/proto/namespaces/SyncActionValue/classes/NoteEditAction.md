# Class: NoteEditAction

Defined in: [WAProto/index.d.ts:46955](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46955)

Represents a NoteEditAction.

## Implements

- [`INoteEditAction`](../interfaces/INoteEditAction.md)

## Constructors

### new NoteEditAction()

> **new NoteEditAction**(`properties`?): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:46961](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46961)

Constructs a new NoteEditAction.

#### Parameters

##### properties?

[`INoteEditAction`](../interfaces/INoteEditAction.md)

Properties to set

#### Returns

[`NoteEditAction`](NoteEditAction.md)

## Properties

### chatJid?

> `optional` **chatJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46967](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46967)

NoteEditAction chatJid.

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`chatJid`](../interfaces/INoteEditAction.md#chatjid)

***

### createdAt?

> `optional` **createdAt**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:46970](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46970)

NoteEditAction createdAt.

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`createdAt`](../interfaces/INoteEditAction.md#createdat)

***

### deleted?

> `optional` **deleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:46973](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46973)

NoteEditAction deleted.

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`deleted`](../interfaces/INoteEditAction.md#deleted)

***

### type?

> `optional` **type**: `null` \| [`NoteType`](../namespaces/NoteEditAction/enumerations/NoteType.md)

Defined in: [WAProto/index.d.ts:46964](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46964)

NoteEditAction type.

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`type`](../interfaces/INoteEditAction.md#type)

***

### unstructuredContent?

> `optional` **unstructuredContent**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46976](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46976)

NoteEditAction unstructuredContent.

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`unstructuredContent`](../interfaces/INoteEditAction.md#unstructuredcontent)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:47046](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47046)

Converts this NoteEditAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:46983](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46983)

Creates a new NoteEditAction instance using the specified properties.

#### Parameters

##### properties?

[`INoteEditAction`](../interfaces/INoteEditAction.md)

Properties to set

#### Returns

[`NoteEditAction`](NoteEditAction.md)

NoteEditAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:47009](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47009)

Decodes a NoteEditAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NoteEditAction`](NoteEditAction.md)

NoteEditAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:47018](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47018)

Decodes a NoteEditAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NoteEditAction`](NoteEditAction.md)

NoteEditAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46991](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46991)

Encodes the specified NoteEditAction message. Does not implicitly [verify](NoteEditAction.md#verify) messages.

#### Parameters

##### message

[`INoteEditAction`](../interfaces/INoteEditAction.md)

NoteEditAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46999](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L46999)

Encodes the specified NoteEditAction message, length delimited. Does not implicitly [verify](NoteEditAction.md#verify) messages.

#### Parameters

##### message

[`INoteEditAction`](../interfaces/INoteEditAction.md)

NoteEditAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:47032](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47032)

Creates a NoteEditAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NoteEditAction`](NoteEditAction.md)

NoteEditAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:47053](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47053)

Gets the default type url for NoteEditAction

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

Defined in: [WAProto/index.d.ts:47040](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47040)

Creates a plain object from a NoteEditAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`NoteEditAction`](NoteEditAction.md)

NoteEditAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:47025](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47025)

Verifies a NoteEditAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
