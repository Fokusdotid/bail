# Class: StatusNotificationMessage

Defined in: [WAProto/index.d.ts:33867](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33867)

Represents a StatusNotificationMessage.

## Implements

- [`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

## Constructors

### new StatusNotificationMessage()

> **new StatusNotificationMessage**(`properties`?): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:33873](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33873)

Constructs a new StatusNotificationMessage.

#### Parameters

##### properties?

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

Properties to set

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

## Properties

### originalMessageKey?

> `optional` **originalMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:33879](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33879)

StatusNotificationMessage originalMessageKey.

#### Implementation of

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md).[`originalMessageKey`](../interfaces/IStatusNotificationMessage.md#originalmessagekey)

***

### responseMessageKey?

> `optional` **responseMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:33876](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33876)

StatusNotificationMessage responseMessageKey.

#### Implementation of

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md).[`responseMessageKey`](../interfaces/IStatusNotificationMessage.md#responsemessagekey)

***

### type?

> `optional` **type**: `null` \| [`StatusNotificationType`](../namespaces/StatusNotificationMessage/enumerations/StatusNotificationType.md)

Defined in: [WAProto/index.d.ts:33882](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33882)

StatusNotificationMessage type.

#### Implementation of

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md).[`type`](../interfaces/IStatusNotificationMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33952](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33952)

Converts this StatusNotificationMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:33889](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33889)

Creates a new StatusNotificationMessage instance using the specified properties.

#### Parameters

##### properties?

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

Properties to set

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

StatusNotificationMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:33915](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33915)

Decodes a StatusNotificationMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

StatusNotificationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:33924](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33924)

Decodes a StatusNotificationMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

StatusNotificationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33897](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33897)

Encodes the specified StatusNotificationMessage message. Does not implicitly [verify](StatusNotificationMessage.md#verify) messages.

#### Parameters

##### message

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

StatusNotificationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33905](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33905)

Encodes the specified StatusNotificationMessage message, length delimited. Does not implicitly [verify](StatusNotificationMessage.md#verify) messages.

#### Parameters

##### message

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

StatusNotificationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:33938](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33938)

Creates a StatusNotificationMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

StatusNotificationMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:33959](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33959)

Gets the default type url for StatusNotificationMessage

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

Defined in: [WAProto/index.d.ts:33946](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33946)

Creates a plain object from a StatusNotificationMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`StatusNotificationMessage`](StatusNotificationMessage.md)

StatusNotificationMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33931](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L33931)

Verifies a StatusNotificationMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
