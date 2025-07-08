# Class: BotLinkedAccount

Defined in: [WAProto/index.d.ts:4105](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4105)

Represents a BotLinkedAccount.

## Implements

- [`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

## Constructors

### new BotLinkedAccount()

> **new BotLinkedAccount**(`properties`?): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:4111](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4111)

Constructs a new BotLinkedAccount.

#### Parameters

##### properties?

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

Properties to set

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

## Properties

### type?

> `optional` **type**: `null` \| [`BOT_LINKED_ACCOUNT_TYPE_1P`](../namespaces/BotLinkedAccount/enumerations/BotLinkedAccountType.md#bot_linked_account_type_1p)

Defined in: [WAProto/index.d.ts:4114](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4114)

BotLinkedAccount type.

#### Implementation of

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md).[`type`](../interfaces/IBotLinkedAccount.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4184](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4184)

Converts this BotLinkedAccount to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:4121](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4121)

Creates a new BotLinkedAccount instance using the specified properties.

#### Parameters

##### properties?

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

Properties to set

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

BotLinkedAccount instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:4147](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4147)

Decodes a BotLinkedAccount message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

BotLinkedAccount

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:4156](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4156)

Decodes a BotLinkedAccount message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

BotLinkedAccount

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4129](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4129)

Encodes the specified BotLinkedAccount message. Does not implicitly [verify](BotLinkedAccount.md#verify) messages.

#### Parameters

##### message

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

BotLinkedAccount message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4137](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4137)

Encodes the specified BotLinkedAccount message, length delimited. Does not implicitly [verify](BotLinkedAccount.md#verify) messages.

#### Parameters

##### message

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

BotLinkedAccount message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:4170](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4170)

Creates a BotLinkedAccount message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

BotLinkedAccount

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4191](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4191)

Gets the default type url for BotLinkedAccount

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

Defined in: [WAProto/index.d.ts:4178](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4178)

Creates a plain object from a BotLinkedAccount message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotLinkedAccount`](BotLinkedAccount.md)

BotLinkedAccount

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4163](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L4163)

Verifies a BotLinkedAccount message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
