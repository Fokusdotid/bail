# Class: AppStateSyncKeyData

Defined in: [WAProto/index.d.ts:19273](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19273)

Represents an AppStateSyncKeyData.

## Implements

- [`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

## Constructors

### new AppStateSyncKeyData()

> **new AppStateSyncKeyData**(`properties`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:19279](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19279)

Constructs a new AppStateSyncKeyData.

#### Parameters

##### properties?

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

Properties to set

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

## Properties

### fingerprint?

> `optional` **fingerprint**: `null` \| [`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:19285](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19285)

AppStateSyncKeyData fingerprint.

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`fingerprint`](../interfaces/IAppStateSyncKeyData.md#fingerprint)

***

### keyData?

> `optional` **keyData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:19282](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19282)

AppStateSyncKeyData keyData.

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`keyData`](../interfaces/IAppStateSyncKeyData.md#keydata)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:19288](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19288)

AppStateSyncKeyData timestamp.

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`timestamp`](../interfaces/IAppStateSyncKeyData.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19358](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19358)

Converts this AppStateSyncKeyData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:19295](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19295)

Creates a new AppStateSyncKeyData instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

Properties to set

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:19321](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19321)

Decodes an AppStateSyncKeyData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:19330](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19330)

Decodes an AppStateSyncKeyData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19303](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19303)

Encodes the specified AppStateSyncKeyData message. Does not implicitly [verify](AppStateSyncKeyData.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

AppStateSyncKeyData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19311](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19311)

Encodes the specified AppStateSyncKeyData message, length delimited. Does not implicitly [verify](AppStateSyncKeyData.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

AppStateSyncKeyData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:19344](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19344)

Creates an AppStateSyncKeyData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:19365](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19365)

Gets the default type url for AppStateSyncKeyData

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

Defined in: [WAProto/index.d.ts:19352](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19352)

Creates a plain object from an AppStateSyncKeyData message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

AppStateSyncKeyData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19337](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19337)

Verifies an AppStateSyncKeyData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
