# Class: PrivacySettingRelayAllCalls

Defined in: [WAProto/index.d.ts:47971](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L47971)

Represents a PrivacySettingRelayAllCalls.

## Implements

- [`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

## Constructors

### new PrivacySettingRelayAllCalls()

> **new PrivacySettingRelayAllCalls**(`properties`?): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:47977](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L47977)

Constructs a new PrivacySettingRelayAllCalls.

#### Parameters

##### properties?

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

Properties to set

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

## Properties

### isEnabled?

> `optional` **isEnabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:47980](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L47980)

PrivacySettingRelayAllCalls isEnabled.

#### Implementation of

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md).[`isEnabled`](../interfaces/IPrivacySettingRelayAllCalls.md#isenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48050](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48050)

Converts this PrivacySettingRelayAllCalls to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:47987](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L47987)

Creates a new PrivacySettingRelayAllCalls instance using the specified properties.

#### Parameters

##### properties?

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

Properties to set

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:48013](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48013)

Decodes a PrivacySettingRelayAllCalls message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:48022](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48022)

Decodes a PrivacySettingRelayAllCalls message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47995](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L47995)

Encodes the specified PrivacySettingRelayAllCalls message. Does not implicitly [verify](PrivacySettingRelayAllCalls.md#verify) messages.

#### Parameters

##### message

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48003](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48003)

Encodes the specified PrivacySettingRelayAllCalls message, length delimited. Does not implicitly [verify](PrivacySettingRelayAllCalls.md#verify) messages.

#### Parameters

##### message

[`IPrivacySettingRelayAllCalls`](../interfaces/IPrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

Defined in: [WAProto/index.d.ts:48036](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48036)

Creates a PrivacySettingRelayAllCalls message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48057](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48057)

Gets the default type url for PrivacySettingRelayAllCalls

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

Defined in: [WAProto/index.d.ts:48044](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48044)

Creates a plain object from a PrivacySettingRelayAllCalls message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrivacySettingRelayAllCalls`](PrivacySettingRelayAllCalls.md)

PrivacySettingRelayAllCalls

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48029](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L48029)

Verifies a PrivacySettingRelayAllCalls message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
