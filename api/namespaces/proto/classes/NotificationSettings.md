# Class: NotificationSettings

Defined in: [WAProto/index.d.ts:37698](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37698)

Represents a NotificationSettings.

## Implements

- [`INotificationSettings`](../interfaces/INotificationSettings.md)

## Constructors

### new NotificationSettings()

> **new NotificationSettings**(`properties`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:37704](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37704)

Constructs a new NotificationSettings.

#### Parameters

##### properties?

[`INotificationSettings`](../interfaces/INotificationSettings.md)

Properties to set

#### Returns

[`NotificationSettings`](NotificationSettings.md)

## Properties

### callVibrate?

> `optional` **callVibrate**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37722](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37722)

NotificationSettings callVibrate.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`callVibrate`](../interfaces/INotificationSettings.md#callvibrate)

***

### lowPriorityNotifications?

> `optional` **lowPriorityNotifications**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:37716](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37716)

NotificationSettings lowPriorityNotifications.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`lowPriorityNotifications`](../interfaces/INotificationSettings.md#lowprioritynotifications)

***

### messageLight?

> `optional` **messageLight**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37713](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37713)

NotificationSettings messageLight.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messageLight`](../interfaces/INotificationSettings.md#messagelight)

***

### messagePopup?

> `optional` **messagePopup**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37710](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37710)

NotificationSettings messagePopup.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messagePopup`](../interfaces/INotificationSettings.md#messagepopup)

***

### messageVibrate?

> `optional` **messageVibrate**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37707](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37707)

NotificationSettings messageVibrate.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messageVibrate`](../interfaces/INotificationSettings.md#messagevibrate)

***

### reactionsMuted?

> `optional` **reactionsMuted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:37719](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37719)

NotificationSettings reactionsMuted.

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`reactionsMuted`](../interfaces/INotificationSettings.md#reactionsmuted)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37792](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37792)

Converts this NotificationSettings to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:37729](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37729)

Creates a new NotificationSettings instance using the specified properties.

#### Parameters

##### properties?

[`INotificationSettings`](../interfaces/INotificationSettings.md)

Properties to set

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:37755](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37755)

Decodes a NotificationSettings message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:37764](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37764)

Decodes a NotificationSettings message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37737](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37737)

Encodes the specified NotificationSettings message. Does not implicitly [verify](NotificationSettings.md#verify) messages.

#### Parameters

##### message

[`INotificationSettings`](../interfaces/INotificationSettings.md)

NotificationSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37745](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37745)

Encodes the specified NotificationSettings message, length delimited. Does not implicitly [verify](NotificationSettings.md#verify) messages.

#### Parameters

##### message

[`INotificationSettings`](../interfaces/INotificationSettings.md)

NotificationSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:37778](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37778)

Creates a NotificationSettings message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:37799](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37799)

Gets the default type url for NotificationSettings

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

Defined in: [WAProto/index.d.ts:37786](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37786)

Creates a plain object from a NotificationSettings message. Also converts values to other types if specified.

#### Parameters

##### message

[`NotificationSettings`](NotificationSettings.md)

NotificationSettings

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:37771](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L37771)

Verifies a NotificationSettings message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
