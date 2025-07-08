# Class: PnForLidChatAction

Defined in: [WAProto/index.d.ts:47583](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47583)

Represents a PnForLidChatAction.

## Implements

- [`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

## Constructors

### new PnForLidChatAction()

> **new PnForLidChatAction**(`properties`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:47589](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47589)

Constructs a new PnForLidChatAction.

#### Parameters

##### properties?

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

Properties to set

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

## Properties

### pnJid?

> `optional` **pnJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:47592](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47592)

PnForLidChatAction pnJid.

#### Implementation of

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md).[`pnJid`](../interfaces/IPnForLidChatAction.md#pnjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:47662](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47662)

Converts this PnForLidChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:47599](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47599)

Creates a new PnForLidChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

Properties to set

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:47625](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47625)

Decodes a PnForLidChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:47634](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47634)

Decodes a PnForLidChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47607](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47607)

Encodes the specified PnForLidChatAction message. Does not implicitly [verify](PnForLidChatAction.md#verify) messages.

#### Parameters

##### message

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

PnForLidChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47615](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47615)

Encodes the specified PnForLidChatAction message, length delimited. Does not implicitly [verify](PnForLidChatAction.md#verify) messages.

#### Parameters

##### message

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

PnForLidChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:47648](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47648)

Creates a PnForLidChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:47669](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47669)

Gets the default type url for PnForLidChatAction

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

Defined in: [WAProto/index.d.ts:47656](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47656)

Creates a plain object from a PnForLidChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PnForLidChatAction`](PnForLidChatAction.md)

PnForLidChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:47641](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L47641)

Verifies a PnForLidChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
