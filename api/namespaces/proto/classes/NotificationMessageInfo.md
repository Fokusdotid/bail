# Class: NotificationMessageInfo

Defined in: [WAProto/index.d.ts:37577](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37577)

Represents a NotificationMessageInfo.

## Implements

- [`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

## Constructors

### new NotificationMessageInfo()

> **new NotificationMessageInfo**(`properties`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:37583](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37583)

Constructs a new NotificationMessageInfo.

#### Parameters

##### properties?

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

Properties to set

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:37586](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37586)

NotificationMessageInfo key.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`key`](../interfaces/INotificationMessageInfo.md#key)

***

### message?

> `optional` **message**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:37589](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37589)

NotificationMessageInfo message.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`message`](../interfaces/INotificationMessageInfo.md#message)

***

### messageTimestamp?

> `optional` **messageTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:37592](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37592)

NotificationMessageInfo messageTimestamp.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`messageTimestamp`](../interfaces/INotificationMessageInfo.md#messagetimestamp)

***

### participant?

> `optional` **participant**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37595](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37595)

NotificationMessageInfo participant.

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`participant`](../interfaces/INotificationMessageInfo.md#participant)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37665](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37665)

Converts this NotificationMessageInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:37602](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37602)

Creates a new NotificationMessageInfo instance using the specified properties.

#### Parameters

##### properties?

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

Properties to set

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:37628](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37628)

Decodes a NotificationMessageInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:37637](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37637)

Decodes a NotificationMessageInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37610](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37610)

Encodes the specified NotificationMessageInfo message. Does not implicitly [verify](NotificationMessageInfo.md#verify) messages.

#### Parameters

##### message

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

NotificationMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37618](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37618)

Encodes the specified NotificationMessageInfo message, length delimited. Does not implicitly [verify](NotificationMessageInfo.md#verify) messages.

#### Parameters

##### message

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

NotificationMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:37651](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37651)

Creates a NotificationMessageInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:37672](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37672)

Gets the default type url for NotificationMessageInfo

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

Defined in: [WAProto/index.d.ts:37659](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37659)

Creates a plain object from a NotificationMessageInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`NotificationMessageInfo`](NotificationMessageInfo.md)

NotificationMessageInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:37644](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L37644)

Verifies a NotificationMessageInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
