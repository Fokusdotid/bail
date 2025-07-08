# Class: CloudAPIThreadControlNotification

Defined in: [WAProto/index.d.ts:21469](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21469)

Represents a CloudAPIThreadControlNotification.

## Implements

- [`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

## Constructors

### new CloudAPIThreadControlNotification()

> **new CloudAPIThreadControlNotification**(`properties`?): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:21475](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21475)

Constructs a new CloudAPIThreadControlNotification.

#### Parameters

##### properties?

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

Properties to set

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

## Properties

### consumerLid?

> `optional` **consumerLid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21484](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21484)

CloudAPIThreadControlNotification consumerLid.

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`consumerLid`](../interfaces/ICloudAPIThreadControlNotification.md#consumerlid)

***

### consumerPhoneNumber?

> `optional` **consumerPhoneNumber**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21487](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21487)

CloudAPIThreadControlNotification consumerPhoneNumber.

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`consumerPhoneNumber`](../interfaces/ICloudAPIThreadControlNotification.md#consumerphonenumber)

***

### notificationContent?

> `optional` **notificationContent**: `null` \| [`ICloudAPIThreadControlNotificationContent`](../namespaces/CloudAPIThreadControlNotification/interfaces/ICloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:21490](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21490)

CloudAPIThreadControlNotification notificationContent.

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`notificationContent`](../interfaces/ICloudAPIThreadControlNotification.md#notificationcontent)

***

### senderNotificationTimestampMs?

> `optional` **senderNotificationTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:21481](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21481)

CloudAPIThreadControlNotification senderNotificationTimestampMs.

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`senderNotificationTimestampMs`](../interfaces/ICloudAPIThreadControlNotification.md#sendernotificationtimestampms)

***

### status?

> `optional` **status**: `null` \| [`CloudAPIThreadControl`](../namespaces/CloudAPIThreadControlNotification/enumerations/CloudAPIThreadControl.md)

Defined in: [WAProto/index.d.ts:21478](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21478)

CloudAPIThreadControlNotification status.

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`status`](../interfaces/ICloudAPIThreadControlNotification.md#status)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21560](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21560)

Converts this CloudAPIThreadControlNotification to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:21497](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21497)

Creates a new CloudAPIThreadControlNotification instance using the specified properties.

#### Parameters

##### properties?

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

Properties to set

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

CloudAPIThreadControlNotification instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:21523](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21523)

Decodes a CloudAPIThreadControlNotification message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

CloudAPIThreadControlNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:21532](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21532)

Decodes a CloudAPIThreadControlNotification message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

CloudAPIThreadControlNotification

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21505](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21505)

Encodes the specified CloudAPIThreadControlNotification message. Does not implicitly [verify](CloudAPIThreadControlNotification.md#verify) messages.

#### Parameters

##### message

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

CloudAPIThreadControlNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21513](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21513)

Encodes the specified CloudAPIThreadControlNotification message, length delimited. Does not implicitly [verify](CloudAPIThreadControlNotification.md#verify) messages.

#### Parameters

##### message

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

CloudAPIThreadControlNotification message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:21546](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21546)

Creates a CloudAPIThreadControlNotification message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

CloudAPIThreadControlNotification

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21567](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21567)

Gets the default type url for CloudAPIThreadControlNotification

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

Defined in: [WAProto/index.d.ts:21554](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21554)

Creates a plain object from a CloudAPIThreadControlNotification message. Also converts values to other types if specified.

#### Parameters

##### message

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

CloudAPIThreadControlNotification

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21539](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L21539)

Verifies a CloudAPIThreadControlNotification message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
