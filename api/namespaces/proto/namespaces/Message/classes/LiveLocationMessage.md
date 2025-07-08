# Class: LiveLocationMessage

Defined in: [WAProto/index.d.ts:27736](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27736)

Represents a LiveLocationMessage.

## Implements

- [`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

## Constructors

### new LiveLocationMessage()

> **new LiveLocationMessage**(`properties`?): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:27742](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27742)

Constructs a new LiveLocationMessage.

#### Parameters

##### properties?

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

Properties to set

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

## Properties

### accuracyInMeters?

> `optional` **accuracyInMeters**: `null` \| `number`

Defined in: [WAProto/index.d.ts:27751](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27751)

LiveLocationMessage accuracyInMeters.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`accuracyInMeters`](../interfaces/ILiveLocationMessage.md#accuracyinmeters)

***

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:27760](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27760)

LiveLocationMessage caption.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`caption`](../interfaces/ILiveLocationMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:27772](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27772)

LiveLocationMessage contextInfo.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`contextInfo`](../interfaces/ILiveLocationMessage.md#contextinfo)

***

### degreesClockwiseFromMagneticNorth?

> `optional` **degreesClockwiseFromMagneticNorth**: `null` \| `number`

Defined in: [WAProto/index.d.ts:27757](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27757)

LiveLocationMessage degreesClockwiseFromMagneticNorth.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`degreesClockwiseFromMagneticNorth`](../interfaces/ILiveLocationMessage.md#degreesclockwisefrommagneticnorth)

***

### degreesLatitude?

> `optional` **degreesLatitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:27745](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27745)

LiveLocationMessage degreesLatitude.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`degreesLatitude`](../interfaces/ILiveLocationMessage.md#degreeslatitude)

***

### degreesLongitude?

> `optional` **degreesLongitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:27748](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27748)

LiveLocationMessage degreesLongitude.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`degreesLongitude`](../interfaces/ILiveLocationMessage.md#degreeslongitude)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:27769](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27769)

LiveLocationMessage jpegThumbnail.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`jpegThumbnail`](../interfaces/ILiveLocationMessage.md#jpegthumbnail)

***

### sequenceNumber?

> `optional` **sequenceNumber**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:27763](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27763)

LiveLocationMessage sequenceNumber.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`sequenceNumber`](../interfaces/ILiveLocationMessage.md#sequencenumber)

***

### speedInMps?

> `optional` **speedInMps**: `null` \| `number`

Defined in: [WAProto/index.d.ts:27754](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27754)

LiveLocationMessage speedInMps.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`speedInMps`](../interfaces/ILiveLocationMessage.md#speedinmps)

***

### timeOffset?

> `optional` **timeOffset**: `null` \| `number`

Defined in: [WAProto/index.d.ts:27766](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27766)

LiveLocationMessage timeOffset.

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`timeOffset`](../interfaces/ILiveLocationMessage.md#timeoffset)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:27842](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27842)

Converts this LiveLocationMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:27779](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27779)

Creates a new LiveLocationMessage instance using the specified properties.

#### Parameters

##### properties?

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

Properties to set

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

LiveLocationMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:27805](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27805)

Decodes a LiveLocationMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

LiveLocationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:27814](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27814)

Decodes a LiveLocationMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

LiveLocationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27787](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27787)

Encodes the specified LiveLocationMessage message. Does not implicitly [verify](LiveLocationMessage.md#verify) messages.

#### Parameters

##### message

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

LiveLocationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:27795](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27795)

Encodes the specified LiveLocationMessage message, length delimited. Does not implicitly [verify](LiveLocationMessage.md#verify) messages.

#### Parameters

##### message

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

LiveLocationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:27828](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27828)

Creates a LiveLocationMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

LiveLocationMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:27849](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27849)

Gets the default type url for LiveLocationMessage

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

Defined in: [WAProto/index.d.ts:27836](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27836)

Creates a plain object from a LiveLocationMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`LiveLocationMessage`](LiveLocationMessage.md)

LiveLocationMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:27821](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L27821)

Verifies a LiveLocationMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
