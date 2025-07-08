# Class: DeviceSentMessage

Defined in: [WAProto/index.d.ts:22115](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22115)

Represents a DeviceSentMessage.

## Implements

- [`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

## Constructors

### new DeviceSentMessage()

> **new DeviceSentMessage**(`properties`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:22121](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22121)

Constructs a new DeviceSentMessage.

#### Parameters

##### properties?

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

Properties to set

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

## Properties

### destinationJid?

> `optional` **destinationJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:22124](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22124)

DeviceSentMessage destinationJid.

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`destinationJid`](../interfaces/IDeviceSentMessage.md#destinationjid)

***

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:22127](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22127)

DeviceSentMessage message.

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`message`](../interfaces/IDeviceSentMessage.md#message)

***

### phash?

> `optional` **phash**: `null` \| `string`

Defined in: [WAProto/index.d.ts:22130](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22130)

DeviceSentMessage phash.

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`phash`](../interfaces/IDeviceSentMessage.md#phash)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22200](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22200)

Converts this DeviceSentMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:22137](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22137)

Creates a new DeviceSentMessage instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

Properties to set

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:22163](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22163)

Decodes a DeviceSentMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:22172](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22172)

Decodes a DeviceSentMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22145](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22145)

Encodes the specified DeviceSentMessage message. Does not implicitly [verify](DeviceSentMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

DeviceSentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22153](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22153)

Encodes the specified DeviceSentMessage message, length delimited. Does not implicitly [verify](DeviceSentMessage.md#verify) messages.

#### Parameters

##### message

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

DeviceSentMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:22186](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22186)

Creates a DeviceSentMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:22207](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22207)

Gets the default type url for DeviceSentMessage

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

Defined in: [WAProto/index.d.ts:22194](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22194)

Creates a plain object from a DeviceSentMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceSentMessage`](DeviceSentMessage.md)

DeviceSentMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22179](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L22179)

Verifies a DeviceSentMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
