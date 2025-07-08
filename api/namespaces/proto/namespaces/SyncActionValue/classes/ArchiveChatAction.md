# Class: ArchiveChatAction

Defined in: [WAProto/index.d.ts:43894](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43894)

Represents an ArchiveChatAction.

## Implements

- [`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

## Constructors

### new ArchiveChatAction()

> **new ArchiveChatAction**(`properties`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:43900](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43900)

Constructs a new ArchiveChatAction.

#### Parameters

##### properties?

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

Properties to set

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

## Properties

### archived?

> `optional` **archived**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:43903](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43903)

ArchiveChatAction archived.

#### Implementation of

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md).[`archived`](../interfaces/IArchiveChatAction.md#archived)

***

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:43906](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43906)

ArchiveChatAction messageRange.

#### Implementation of

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md).[`messageRange`](../interfaces/IArchiveChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:43976](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43976)

Converts this ArchiveChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:43913](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43913)

Creates a new ArchiveChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

Properties to set

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:43939](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43939)

Decodes an ArchiveChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:43948](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43948)

Decodes an ArchiveChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:43921](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43921)

Encodes the specified ArchiveChatAction message. Does not implicitly [verify](ArchiveChatAction.md#verify) messages.

#### Parameters

##### message

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

ArchiveChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:43929](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43929)

Encodes the specified ArchiveChatAction message, length delimited. Does not implicitly [verify](ArchiveChatAction.md#verify) messages.

#### Parameters

##### message

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

ArchiveChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:43962](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43962)

Creates an ArchiveChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:43983](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43983)

Gets the default type url for ArchiveChatAction

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

Defined in: [WAProto/index.d.ts:43970](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43970)

Creates a plain object from an ArchiveChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ArchiveChatAction`](ArchiveChatAction.md)

ArchiveChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:43955](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L43955)

Verifies an ArchiveChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
