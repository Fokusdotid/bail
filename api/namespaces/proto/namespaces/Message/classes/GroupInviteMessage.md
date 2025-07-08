# Class: GroupInviteMessage

Defined in: [WAProto/index.d.ts:23540](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23540)

Represents a GroupInviteMessage.

## Implements

- [`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

## Constructors

### new GroupInviteMessage()

> **new GroupInviteMessage**(`properties`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:23546](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23546)

Constructs a new GroupInviteMessage.

#### Parameters

##### properties?

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

Properties to set

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

## Properties

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:23564](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23564)

GroupInviteMessage caption.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`caption`](../interfaces/IGroupInviteMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:23567](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23567)

GroupInviteMessage contextInfo.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`contextInfo`](../interfaces/IGroupInviteMessage.md#contextinfo)

***

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:23549](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23549)

GroupInviteMessage groupJid.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupJid`](../interfaces/IGroupInviteMessage.md#groupjid)

***

### groupName?

> `optional` **groupName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:23558](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23558)

GroupInviteMessage groupName.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupName`](../interfaces/IGroupInviteMessage.md#groupname)

***

### groupType?

> `optional` **groupType**: `null` \| [`GroupType`](../namespaces/GroupInviteMessage/enumerations/GroupType.md)

Defined in: [WAProto/index.d.ts:23570](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23570)

GroupInviteMessage groupType.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupType`](../interfaces/IGroupInviteMessage.md#grouptype)

***

### inviteCode?

> `optional` **inviteCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:23552](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23552)

GroupInviteMessage inviteCode.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`inviteCode`](../interfaces/IGroupInviteMessage.md#invitecode)

***

### inviteExpiration?

> `optional` **inviteExpiration**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:23555](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23555)

GroupInviteMessage inviteExpiration.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`inviteExpiration`](../interfaces/IGroupInviteMessage.md#inviteexpiration)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:23561](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23561)

GroupInviteMessage jpegThumbnail.

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`jpegThumbnail`](../interfaces/IGroupInviteMessage.md#jpegthumbnail)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23640](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23640)

Converts this GroupInviteMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:23577](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23577)

Creates a new GroupInviteMessage instance using the specified properties.

#### Parameters

##### properties?

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

Properties to set

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:23603](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23603)

Decodes a GroupInviteMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:23612](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23612)

Decodes a GroupInviteMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23585](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23585)

Encodes the specified GroupInviteMessage message. Does not implicitly [verify](GroupInviteMessage.md#verify) messages.

#### Parameters

##### message

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

GroupInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23593](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23593)

Encodes the specified GroupInviteMessage message, length delimited. Does not implicitly [verify](GroupInviteMessage.md#verify) messages.

#### Parameters

##### message

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

GroupInviteMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:23626](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23626)

Creates a GroupInviteMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:23647](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23647)

Gets the default type url for GroupInviteMessage

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

Defined in: [WAProto/index.d.ts:23634](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23634)

Creates a plain object from a GroupInviteMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`GroupInviteMessage`](GroupInviteMessage.md)

GroupInviteMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23619](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L23619)

Verifies a GroupInviteMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
