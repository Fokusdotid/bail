# Class: BotMetricsMetadata

Defined in: [WAProto/index.d.ts:5040](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5040)

Represents a BotMetricsMetadata.

## Implements

- [`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

## Constructors

### new BotMetricsMetadata()

> **new BotMetricsMetadata**(`properties`?): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:5046](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5046)

Constructs a new BotMetricsMetadata.

#### Parameters

##### properties?

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

Properties to set

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

## Properties

### destinationEntryPoint?

> `optional` **destinationEntryPoint**: `null` \| [`BotMetricsEntryPoint`](../enumerations/BotMetricsEntryPoint.md)

Defined in: [WAProto/index.d.ts:5052](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5052)

BotMetricsMetadata destinationEntryPoint.

#### Implementation of

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md).[`destinationEntryPoint`](../interfaces/IBotMetricsMetadata.md#destinationentrypoint)

***

### destinationId?

> `optional` **destinationId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5049](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5049)

BotMetricsMetadata destinationId.

#### Implementation of

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md).[`destinationId`](../interfaces/IBotMetricsMetadata.md#destinationid)

***

### threadOrigin?

> `optional` **threadOrigin**: `null` \| [`BotMetricsThreadEntryPoint`](../enumerations/BotMetricsThreadEntryPoint.md)

Defined in: [WAProto/index.d.ts:5055](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5055)

BotMetricsMetadata threadOrigin.

#### Implementation of

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md).[`threadOrigin`](../interfaces/IBotMetricsMetadata.md#threadorigin)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5125](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5125)

Converts this BotMetricsMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:5062](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5062)

Creates a new BotMetricsMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

Properties to set

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

BotMetricsMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:5088](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5088)

Decodes a BotMetricsMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

BotMetricsMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:5097](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5097)

Decodes a BotMetricsMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

BotMetricsMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5070](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5070)

Encodes the specified BotMetricsMetadata message. Does not implicitly [verify](BotMetricsMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

BotMetricsMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5078](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5078)

Encodes the specified BotMetricsMetadata message, length delimited. Does not implicitly [verify](BotMetricsMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

BotMetricsMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:5111](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5111)

Creates a BotMetricsMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

BotMetricsMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5132](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5132)

Gets the default type url for BotMetricsMetadata

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

Defined in: [WAProto/index.d.ts:5119](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5119)

Creates a plain object from a BotMetricsMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotMetricsMetadata`](BotMetricsMetadata.md)

BotMetricsMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5104](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L5104)

Verifies a BotMetricsMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
