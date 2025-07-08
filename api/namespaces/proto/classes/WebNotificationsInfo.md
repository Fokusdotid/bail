# Class: WebNotificationsInfo

Defined in: [WAProto/index.d.ts:53376](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53376)

Represents a WebNotificationsInfo.

## Implements

- [`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

## Constructors

### new WebNotificationsInfo()

> **new WebNotificationsInfo**(`properties`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:53382](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53382)

Constructs a new WebNotificationsInfo.

#### Parameters

##### properties?

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

Properties to set

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

## Properties

### notifyMessageCount?

> `optional` **notifyMessageCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:53391](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53391)

WebNotificationsInfo notifyMessageCount.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`notifyMessageCount`](../interfaces/IWebNotificationsInfo.md#notifymessagecount)

***

### notifyMessages

> **notifyMessages**: [`IWebMessageInfo`](../interfaces/IWebMessageInfo.md)[]

Defined in: [WAProto/index.d.ts:53394](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53394)

WebNotificationsInfo notifyMessages.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`notifyMessages`](../interfaces/IWebNotificationsInfo.md#notifymessages)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:53385](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53385)

WebNotificationsInfo timestamp.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`timestamp`](../interfaces/IWebNotificationsInfo.md#timestamp)

***

### unreadChats?

> `optional` **unreadChats**: `null` \| `number`

Defined in: [WAProto/index.d.ts:53388](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53388)

WebNotificationsInfo unreadChats.

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`unreadChats`](../interfaces/IWebNotificationsInfo.md#unreadchats)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:53464](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53464)

Converts this WebNotificationsInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:53401](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53401)

Creates a new WebNotificationsInfo instance using the specified properties.

#### Parameters

##### properties?

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

Properties to set

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:53427](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53427)

Decodes a WebNotificationsInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:53436](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53436)

Decodes a WebNotificationsInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:53409](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53409)

Encodes the specified WebNotificationsInfo message. Does not implicitly [verify](WebNotificationsInfo.md#verify) messages.

#### Parameters

##### message

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

WebNotificationsInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:53417](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53417)

Encodes the specified WebNotificationsInfo message, length delimited. Does not implicitly [verify](WebNotificationsInfo.md#verify) messages.

#### Parameters

##### message

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

WebNotificationsInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:53450](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53450)

Creates a WebNotificationsInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:53471](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53471)

Gets the default type url for WebNotificationsInfo

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

Defined in: [WAProto/index.d.ts:53458](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53458)

Creates a plain object from a WebNotificationsInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`WebNotificationsInfo`](WebNotificationsInfo.md)

WebNotificationsInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:53443](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L53443)

Verifies a WebNotificationsInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
