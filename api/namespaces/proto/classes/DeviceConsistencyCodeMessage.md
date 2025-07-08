# Class: DeviceConsistencyCodeMessage

Defined in: [WAProto/index.d.ts:12951](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12951)

Represents a DeviceConsistencyCodeMessage.

## Implements

- [`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

## Constructors

### new DeviceConsistencyCodeMessage()

> **new DeviceConsistencyCodeMessage**(`properties`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:12957](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12957)

Constructs a new DeviceConsistencyCodeMessage.

#### Parameters

##### properties?

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

Properties to set

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

## Properties

### generation?

> `optional` **generation**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12960](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12960)

DeviceConsistencyCodeMessage generation.

#### Implementation of

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md).[`generation`](../interfaces/IDeviceConsistencyCodeMessage.md#generation)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:12963](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12963)

DeviceConsistencyCodeMessage signature.

#### Implementation of

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md).[`signature`](../interfaces/IDeviceConsistencyCodeMessage.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13033](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13033)

Converts this DeviceConsistencyCodeMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:12970](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12970)

Creates a new DeviceConsistencyCodeMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

Properties to set

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:12996](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12996)

Decodes a DeviceConsistencyCodeMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:13005](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13005)

Decodes a DeviceConsistencyCodeMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12978](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12978)

Encodes the specified DeviceConsistencyCodeMessage message. Does not implicitly [verify](DeviceConsistencyCodeMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12986](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L12986)

Encodes the specified DeviceConsistencyCodeMessage message, length delimited. Does not implicitly [verify](DeviceConsistencyCodeMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:13019](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13019)

Creates a DeviceConsistencyCodeMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13040](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13040)

Gets the default type url for DeviceConsistencyCodeMessage

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

Defined in: [WAProto/index.d.ts:13027](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13027)

Creates a plain object from a DeviceConsistencyCodeMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

DeviceConsistencyCodeMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13012](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13012)

Verifies a DeviceConsistencyCodeMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
