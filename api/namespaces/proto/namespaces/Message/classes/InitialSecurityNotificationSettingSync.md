# Class: InitialSecurityNotificationSettingSync

Defined in: [WAProto/index.d.ts:24858](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24858)

Represents an InitialSecurityNotificationSettingSync.

## Implements

- [`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

## Constructors

### new InitialSecurityNotificationSettingSync()

> **new InitialSecurityNotificationSettingSync**(`properties`?): [`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:24864](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24864)

Constructs a new InitialSecurityNotificationSettingSync.

#### Parameters

##### properties?

[`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

Properties to set

#### Returns

[`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

## Properties

### securityNotificationEnabled?

> `optional` **securityNotificationEnabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:24867](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24867)

InitialSecurityNotificationSettingSync securityNotificationEnabled.

#### Implementation of

[`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md).[`securityNotificationEnabled`](../interfaces/IInitialSecurityNotificationSettingSync.md#securitynotificationenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24937](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24937)

Converts this InitialSecurityNotificationSettingSync to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:24874](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24874)

Creates a new InitialSecurityNotificationSettingSync instance using the specified properties.

#### Parameters

##### properties?

[`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

Properties to set

#### Returns

[`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

InitialSecurityNotificationSettingSync instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:24900](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24900)

Decodes an InitialSecurityNotificationSettingSync message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

InitialSecurityNotificationSettingSync

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:24909](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24909)

Decodes an InitialSecurityNotificationSettingSync message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

InitialSecurityNotificationSettingSync

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24882](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24882)

Encodes the specified InitialSecurityNotificationSettingSync message. Does not implicitly [verify](InitialSecurityNotificationSettingSync.md#verify) messages.

#### Parameters

##### message

[`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

InitialSecurityNotificationSettingSync message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24890](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24890)

Encodes the specified InitialSecurityNotificationSettingSync message, length delimited. Does not implicitly [verify](InitialSecurityNotificationSettingSync.md#verify) messages.

#### Parameters

##### message

[`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

InitialSecurityNotificationSettingSync message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:24923](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24923)

Creates an InitialSecurityNotificationSettingSync message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

InitialSecurityNotificationSettingSync

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:24944](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24944)

Gets the default type url for InitialSecurityNotificationSettingSync

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

Defined in: [WAProto/index.d.ts:24931](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24931)

Creates a plain object from an InitialSecurityNotificationSettingSync message. Also converts values to other types if specified.

#### Parameters

##### message

[`InitialSecurityNotificationSettingSync`](InitialSecurityNotificationSettingSync.md)

InitialSecurityNotificationSettingSync

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24916](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24916)

Verifies an InitialSecurityNotificationSettingSync message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
