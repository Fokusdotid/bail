# Class: DeviceProps

Defined in: [WAProto/index.d.ts:13202](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13202)

Represents a DeviceProps.

## Implements

- [`IDeviceProps`](../interfaces/IDeviceProps.md)

## Constructors

### new DeviceProps()

> **new DeviceProps**(`properties`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:13208](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13208)

Constructs a new DeviceProps.

#### Parameters

##### properties?

[`IDeviceProps`](../interfaces/IDeviceProps.md)

Properties to set

#### Returns

[`DeviceProps`](DeviceProps.md)

## Properties

### historySyncConfig?

> `optional` **historySyncConfig**: `null` \| [`IHistorySyncConfig`](../namespaces/DeviceProps/interfaces/IHistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:13223](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13223)

DeviceProps historySyncConfig.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`historySyncConfig`](../interfaces/IDeviceProps.md#historysyncconfig)

***

### os?

> `optional` **os**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13211](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13211)

DeviceProps os.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`os`](../interfaces/IDeviceProps.md#os)

***

### platformType?

> `optional` **platformType**: `null` \| [`PlatformType`](../namespaces/DeviceProps/enumerations/PlatformType.md)

Defined in: [WAProto/index.d.ts:13217](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13217)

DeviceProps platformType.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`platformType`](../interfaces/IDeviceProps.md#platformtype)

***

### requireFullSync?

> `optional` **requireFullSync**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:13220](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13220)

DeviceProps requireFullSync.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`requireFullSync`](../interfaces/IDeviceProps.md#requirefullsync)

***

### version?

> `optional` **version**: `null` \| [`IAppVersion`](../namespaces/DeviceProps/interfaces/IAppVersion.md)

Defined in: [WAProto/index.d.ts:13214](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13214)

DeviceProps version.

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`version`](../interfaces/IDeviceProps.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13293](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13293)

Converts this DeviceProps to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:13230](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13230)

Creates a new DeviceProps instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceProps`](../interfaces/IDeviceProps.md)

Properties to set

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:13256](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13256)

Decodes a DeviceProps message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:13265](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13265)

Decodes a DeviceProps message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13238](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13238)

Encodes the specified DeviceProps message. Does not implicitly [verify](DeviceProps.md#verify) messages.

#### Parameters

##### message

[`IDeviceProps`](../interfaces/IDeviceProps.md)

DeviceProps message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13246](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13246)

Encodes the specified DeviceProps message, length delimited. Does not implicitly [verify](DeviceProps.md#verify) messages.

#### Parameters

##### message

[`IDeviceProps`](../interfaces/IDeviceProps.md)

DeviceProps message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:13279](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13279)

Creates a DeviceProps message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceProps`](DeviceProps.md)

DeviceProps

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13300](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13300)

Gets the default type url for DeviceProps

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

Defined in: [WAProto/index.d.ts:13287](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13287)

Creates a plain object from a DeviceProps message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceProps`](DeviceProps.md)

DeviceProps

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13272](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L13272)

Verifies a DeviceProps message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
