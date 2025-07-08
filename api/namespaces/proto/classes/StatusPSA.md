# Class: StatusPSA

Defined in: [WAProto/index.d.ts:42872](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42872)

Represents a StatusPSA.

## Implements

- [`IStatusPSA`](../interfaces/IStatusPSA.md)

## Constructors

### new StatusPSA()

> **new StatusPSA**(`properties`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:42878](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42878)

Constructs a new StatusPSA.

#### Parameters

##### properties?

[`IStatusPSA`](../interfaces/IStatusPSA.md)

Properties to set

#### Returns

[`StatusPSA`](StatusPSA.md)

## Properties

### campaignExpirationTimestamp?

> `optional` **campaignExpirationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:42884](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42884)

StatusPSA campaignExpirationTimestamp.

#### Implementation of

[`IStatusPSA`](../interfaces/IStatusPSA.md).[`campaignExpirationTimestamp`](../interfaces/IStatusPSA.md#campaignexpirationtimestamp)

***

### campaignId

> **campaignId**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:42881](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42881)

StatusPSA campaignId.

#### Implementation of

[`IStatusPSA`](../interfaces/IStatusPSA.md).[`campaignId`](../interfaces/IStatusPSA.md#campaignid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:42954](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42954)

Converts this StatusPSA to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:42891](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42891)

Creates a new StatusPSA instance using the specified properties.

#### Parameters

##### properties?

[`IStatusPSA`](../interfaces/IStatusPSA.md)

Properties to set

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:42917](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42917)

Decodes a StatusPSA message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:42926](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42926)

Decodes a StatusPSA message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42899](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42899)

Encodes the specified StatusPSA message. Does not implicitly [verify](StatusPSA.md#verify) messages.

#### Parameters

##### message

[`IStatusPSA`](../interfaces/IStatusPSA.md)

StatusPSA message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42907](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42907)

Encodes the specified StatusPSA message, length delimited. Does not implicitly [verify](StatusPSA.md#verify) messages.

#### Parameters

##### message

[`IStatusPSA`](../interfaces/IStatusPSA.md)

StatusPSA message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:42940](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42940)

Creates a StatusPSA message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StatusPSA`](StatusPSA.md)

StatusPSA

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:42961](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42961)

Gets the default type url for StatusPSA

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

Defined in: [WAProto/index.d.ts:42948](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42948)

Creates a plain object from a StatusPSA message. Also converts values to other types if specified.

#### Parameters

##### message

[`StatusPSA`](StatusPSA.md)

StatusPSA

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:42933](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L42933)

Verifies a StatusPSA message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
