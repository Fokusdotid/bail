# Class: LimitSharing

Defined in: [WAProto/index.d.ts:17566](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17566)

Represents a LimitSharing.

## Implements

- [`ILimitSharing`](../interfaces/ILimitSharing.md)

## Constructors

### new LimitSharing()

> **new LimitSharing**(`properties`?): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:17572](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17572)

Constructs a new LimitSharing.

#### Parameters

##### properties?

[`ILimitSharing`](../interfaces/ILimitSharing.md)

Properties to set

#### Returns

[`LimitSharing`](LimitSharing.md)

## Properties

### initiatedByMe?

> `optional` **initiatedByMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:17584](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17584)

LimitSharing initiatedByMe.

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`initiatedByMe`](../interfaces/ILimitSharing.md#initiatedbyme)

***

### limitSharingSettingTimestamp?

> `optional` **limitSharingSettingTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:17581](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17581)

LimitSharing limitSharingSettingTimestamp.

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`limitSharingSettingTimestamp`](../interfaces/ILimitSharing.md#limitsharingsettingtimestamp)

***

### sharingLimited?

> `optional` **sharingLimited**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:17575](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17575)

LimitSharing sharingLimited.

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`sharingLimited`](../interfaces/ILimitSharing.md#sharinglimited)

***

### trigger?

> `optional` **trigger**: `null` \| [`TriggerType`](../namespaces/LimitSharing/enumerations/TriggerType.md)

Defined in: [WAProto/index.d.ts:17578](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17578)

LimitSharing trigger.

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`trigger`](../interfaces/ILimitSharing.md#trigger)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17654](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17654)

Converts this LimitSharing to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:17591](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17591)

Creates a new LimitSharing instance using the specified properties.

#### Parameters

##### properties?

[`ILimitSharing`](../interfaces/ILimitSharing.md)

Properties to set

#### Returns

[`LimitSharing`](LimitSharing.md)

LimitSharing instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:17617](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17617)

Decodes a LimitSharing message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LimitSharing`](LimitSharing.md)

LimitSharing

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:17626](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17626)

Decodes a LimitSharing message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LimitSharing`](LimitSharing.md)

LimitSharing

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17599](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17599)

Encodes the specified LimitSharing message. Does not implicitly [verify](LimitSharing.md#verify) messages.

#### Parameters

##### message

[`ILimitSharing`](../interfaces/ILimitSharing.md)

LimitSharing message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17607](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17607)

Encodes the specified LimitSharing message, length delimited. Does not implicitly [verify](LimitSharing.md#verify) messages.

#### Parameters

##### message

[`ILimitSharing`](../interfaces/ILimitSharing.md)

LimitSharing message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:17640](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17640)

Creates a LimitSharing message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LimitSharing`](LimitSharing.md)

LimitSharing

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:17661](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17661)

Gets the default type url for LimitSharing

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

Defined in: [WAProto/index.d.ts:17648](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17648)

Creates a plain object from a LimitSharing message. Also converts values to other types if specified.

#### Parameters

##### message

[`LimitSharing`](LimitSharing.md)

LimitSharing

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17633](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17633)

Verifies a LimitSharing message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
