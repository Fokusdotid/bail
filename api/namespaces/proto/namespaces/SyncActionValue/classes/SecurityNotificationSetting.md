# Class: SecurityNotificationSetting

Defined in: [WAProto/index.d.ts:48480](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48480)

Represents a SecurityNotificationSetting.

## Implements

- [`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

## Constructors

### new SecurityNotificationSetting()

> **new SecurityNotificationSetting**(`properties`?): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:48486](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48486)

Constructs a new SecurityNotificationSetting.

#### Parameters

##### properties?

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

Properties to set

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

## Properties

### showNotification?

> `optional` **showNotification**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:48489](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48489)

SecurityNotificationSetting showNotification.

#### Implementation of

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md).[`showNotification`](../interfaces/ISecurityNotificationSetting.md#shownotification)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48559](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48559)

Converts this SecurityNotificationSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:48496](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48496)

Creates a new SecurityNotificationSetting instance using the specified properties.

#### Parameters

##### properties?

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

Properties to set

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:48522](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48522)

Decodes a SecurityNotificationSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:48531](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48531)

Decodes a SecurityNotificationSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48504](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48504)

Encodes the specified SecurityNotificationSetting message. Does not implicitly [verify](SecurityNotificationSetting.md#verify) messages.

#### Parameters

##### message

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

SecurityNotificationSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48512](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48512)

Encodes the specified SecurityNotificationSetting message, length delimited. Does not implicitly [verify](SecurityNotificationSetting.md#verify) messages.

#### Parameters

##### message

[`ISecurityNotificationSetting`](../interfaces/ISecurityNotificationSetting.md)

SecurityNotificationSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SecurityNotificationSetting`](SecurityNotificationSetting.md)

Defined in: [WAProto/index.d.ts:48545](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48545)

Creates a SecurityNotificationSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48566](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48566)

Gets the default type url for SecurityNotificationSetting

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

Defined in: [WAProto/index.d.ts:48553](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48553)

Creates a plain object from a SecurityNotificationSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`SecurityNotificationSetting`](SecurityNotificationSetting.md)

SecurityNotificationSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48538](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48538)

Verifies a SecurityNotificationSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
