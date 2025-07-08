# Class: BotFeatureQuotaMetadata

Defined in: [WAProto/index.d.ts:6577](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6577)

Represents a BotFeatureQuotaMetadata.

## Implements

- [`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

## Constructors

### new BotFeatureQuotaMetadata()

> **new BotFeatureQuotaMetadata**(`properties`?): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6583](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6583)

Constructs a new BotFeatureQuotaMetadata.

#### Parameters

##### properties?

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

Properties to set

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

## Properties

### expirationTimestamp?

> `optional` **expirationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6592](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6592)

BotFeatureQuotaMetadata expirationTimestamp.

#### Implementation of

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md).[`expirationTimestamp`](../interfaces/IBotFeatureQuotaMetadata.md#expirationtimestamp)

***

### featureType?

> `optional` **featureType**: `null` \| [`BotFeatureType`](../namespaces/BotFeatureQuotaMetadata/enumerations/BotFeatureType.md)

Defined in: [WAProto/index.d.ts:6586](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6586)

BotFeatureQuotaMetadata featureType.

#### Implementation of

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md).[`featureType`](../interfaces/IBotFeatureQuotaMetadata.md#featuretype)

***

### remainingQuota?

> `optional` **remainingQuota**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6589](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6589)

BotFeatureQuotaMetadata remainingQuota.

#### Implementation of

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md).[`remainingQuota`](../interfaces/IBotFeatureQuotaMetadata.md#remainingquota)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6662](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6662)

Converts this BotFeatureQuotaMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6599](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6599)

Creates a new BotFeatureQuotaMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

Properties to set

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

BotFeatureQuotaMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6625](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6625)

Decodes a BotFeatureQuotaMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

BotFeatureQuotaMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6634](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6634)

Decodes a BotFeatureQuotaMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

BotFeatureQuotaMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6607](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6607)

Encodes the specified BotFeatureQuotaMetadata message. Does not implicitly [verify](BotFeatureQuotaMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

BotFeatureQuotaMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6615](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6615)

Encodes the specified BotFeatureQuotaMetadata message, length delimited. Does not implicitly [verify](BotFeatureQuotaMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

BotFeatureQuotaMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6648](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6648)

Creates a BotFeatureQuotaMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

BotFeatureQuotaMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6669](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6669)

Gets the default type url for BotFeatureQuotaMetadata

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

Defined in: [WAProto/index.d.ts:6656](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6656)

Creates a plain object from a BotFeatureQuotaMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

BotFeatureQuotaMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6641](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L6641)

Verifies a BotFeatureQuotaMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
