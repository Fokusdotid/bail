# Class: EphemeralSetting

Defined in: [WAProto/index.d.ts:14247](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14247)

Represents an EphemeralSetting.

## Implements

- [`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

## Constructors

### new EphemeralSetting()

> **new EphemeralSetting**(`properties`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:14253](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14253)

Constructs a new EphemeralSetting.

#### Parameters

##### properties?

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

Properties to set

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

## Properties

### duration?

> `optional` **duration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:14256](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14256)

EphemeralSetting duration.

#### Implementation of

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md).[`duration`](../interfaces/IEphemeralSetting.md#duration)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:14259](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14259)

EphemeralSetting timestamp.

#### Implementation of

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md).[`timestamp`](../interfaces/IEphemeralSetting.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14329](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14329)

Converts this EphemeralSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:14266](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14266)

Creates a new EphemeralSetting instance using the specified properties.

#### Parameters

##### properties?

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

Properties to set

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:14292](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14292)

Decodes an EphemeralSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:14301](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14301)

Decodes an EphemeralSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14274](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14274)

Encodes the specified EphemeralSetting message. Does not implicitly [verify](EphemeralSetting.md#verify) messages.

#### Parameters

##### message

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

EphemeralSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14282](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14282)

Encodes the specified EphemeralSetting message, length delimited. Does not implicitly [verify](EphemeralSetting.md#verify) messages.

#### Parameters

##### message

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

EphemeralSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:14315](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14315)

Creates an EphemeralSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:14336](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14336)

Gets the default type url for EphemeralSetting

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

Defined in: [WAProto/index.d.ts:14323](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14323)

Creates a plain object from an EphemeralSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`EphemeralSetting`](EphemeralSetting.md)

EphemeralSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14308](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L14308)

Verifies an EphemeralSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
