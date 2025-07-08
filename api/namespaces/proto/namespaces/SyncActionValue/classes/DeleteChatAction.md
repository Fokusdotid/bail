# Class: DeleteChatAction

Defined in: [WAProto/index.d.ts:45018](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45018)

Represents a DeleteChatAction.

## Implements

- [`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

## Constructors

### new DeleteChatAction()

> **new DeleteChatAction**(`properties`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:45024](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45024)

Constructs a new DeleteChatAction.

#### Parameters

##### properties?

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

Properties to set

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

## Properties

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:45027](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45027)

DeleteChatAction messageRange.

#### Implementation of

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md).[`messageRange`](../interfaces/IDeleteChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45097](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45097)

Converts this DeleteChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:45034](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45034)

Creates a new DeleteChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

Properties to set

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:45060](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45060)

Decodes a DeleteChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:45069](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45069)

Decodes a DeleteChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45042](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45042)

Encodes the specified DeleteChatAction message. Does not implicitly [verify](DeleteChatAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

DeleteChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45050](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45050)

Encodes the specified DeleteChatAction message, length delimited. Does not implicitly [verify](DeleteChatAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

DeleteChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:45083](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45083)

Creates a DeleteChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45104](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45104)

Gets the default type url for DeleteChatAction

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

Defined in: [WAProto/index.d.ts:45091](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45091)

Creates a plain object from a DeleteChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeleteChatAction`](DeleteChatAction.md)

DeleteChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:45076](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45076)

Verifies a DeleteChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
