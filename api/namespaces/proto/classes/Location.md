# Class: Location

Defined in: [WAProto/index.d.ts:17798](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17798)

Represents a Location.

## Implements

- [`ILocation`](../interfaces/ILocation.md)

## Constructors

### new Location()

> **new Location**(`properties`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:17804](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17804)

Constructs a new Location.

#### Parameters

##### properties?

[`ILocation`](../interfaces/ILocation.md)

Properties to set

#### Returns

[`Location`](Location.md)

## Properties

### degreesLatitude?

> `optional` **degreesLatitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:17807](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17807)

Location degreesLatitude.

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`degreesLatitude`](../interfaces/ILocation.md#degreeslatitude)

***

### degreesLongitude?

> `optional` **degreesLongitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:17810](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17810)

Location degreesLongitude.

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`degreesLongitude`](../interfaces/ILocation.md#degreeslongitude)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:17813](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17813)

Location name.

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`name`](../interfaces/ILocation.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17883](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17883)

Converts this Location to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:17820](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17820)

Creates a new Location instance using the specified properties.

#### Parameters

##### properties?

[`ILocation`](../interfaces/ILocation.md)

Properties to set

#### Returns

[`Location`](Location.md)

Location instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:17846](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17846)

Decodes a Location message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Location`](Location.md)

Location

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:17855](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17855)

Decodes a Location message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Location`](Location.md)

Location

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17828](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17828)

Encodes the specified Location message. Does not implicitly [verify](Location.md#verify) messages.

#### Parameters

##### message

[`ILocation`](../interfaces/ILocation.md)

Location message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17836](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17836)

Encodes the specified Location message, length delimited. Does not implicitly [verify](Location.md#verify) messages.

#### Parameters

##### message

[`ILocation`](../interfaces/ILocation.md)

Location message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:17869](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17869)

Creates a Location message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Location`](Location.md)

Location

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:17890](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17890)

Gets the default type url for Location

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

Defined in: [WAProto/index.d.ts:17877](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17877)

Creates a plain object from a Location message. Also converts values to other types if specified.

#### Parameters

##### message

[`Location`](Location.md)

Location

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17862](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L17862)

Verifies a Location message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
