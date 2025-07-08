# Class: BotQuotaMetadata

Defined in: [WAProto/index.d.ts:6472](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6472)

Represents a BotQuotaMetadata.

## Implements

- [`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

## Constructors

### new BotQuotaMetadata()

> **new BotQuotaMetadata**(`properties`?): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6478](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6478)

Constructs a new BotQuotaMetadata.

#### Parameters

##### properties?

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

Properties to set

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

## Properties

### botFeatureQuotaMetadata

> **botFeatureQuotaMetadata**: [`IBotFeatureQuotaMetadata`](../namespaces/BotQuotaMetadata/interfaces/IBotFeatureQuotaMetadata.md)[]

Defined in: [WAProto/index.d.ts:6481](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6481)

BotQuotaMetadata botFeatureQuotaMetadata.

#### Implementation of

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md).[`botFeatureQuotaMetadata`](../interfaces/IBotQuotaMetadata.md#botfeaturequotametadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6551](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6551)

Converts this BotQuotaMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6488](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6488)

Creates a new BotQuotaMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

Properties to set

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

BotQuotaMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6514](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6514)

Decodes a BotQuotaMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

BotQuotaMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6523](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6523)

Decodes a BotQuotaMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

BotQuotaMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6496](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6496)

Encodes the specified BotQuotaMetadata message. Does not implicitly [verify](BotQuotaMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

BotQuotaMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6504](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6504)

Encodes the specified BotQuotaMetadata message, length delimited. Does not implicitly [verify](BotQuotaMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

BotQuotaMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:6537](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6537)

Creates a BotQuotaMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

BotQuotaMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6558](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6558)

Gets the default type url for BotQuotaMetadata

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

Defined in: [WAProto/index.d.ts:6545](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6545)

Creates a plain object from a BotQuotaMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotQuotaMetadata`](BotQuotaMetadata.md)

BotQuotaMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6530](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L6530)

Verifies a BotQuotaMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
