# Class: BotPromotionMessageMetadata

Defined in: [WAProto/index.d.ts:6163](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6163)

Represents a BotPromotionMessageMetadata.

## Implements

- [`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

## Constructors

### new BotPromotionMessageMetadata()

> **new BotPromotionMessageMetadata**(`properties`?): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:6169](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6169)

Constructs a new BotPromotionMessageMetadata.

#### Parameters

##### properties?

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

Properties to set

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

## Properties

### buttonTitle?

> `optional` **buttonTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6175](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6175)

BotPromotionMessageMetadata buttonTitle.

#### Implementation of

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md).[`buttonTitle`](../interfaces/IBotPromotionMessageMetadata.md#buttontitle)

***

### promotionType?

> `optional` **promotionType**: `null` \| [`BotPromotionType`](../namespaces/BotPromotionMessageMetadata/enumerations/BotPromotionType.md)

Defined in: [WAProto/index.d.ts:6172](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6172)

BotPromotionMessageMetadata promotionType.

#### Implementation of

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md).[`promotionType`](../interfaces/IBotPromotionMessageMetadata.md#promotiontype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6245](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6245)

Converts this BotPromotionMessageMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:6182](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6182)

Creates a new BotPromotionMessageMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

Properties to set

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

BotPromotionMessageMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:6208](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6208)

Decodes a BotPromotionMessageMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

BotPromotionMessageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:6217](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6217)

Decodes a BotPromotionMessageMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

BotPromotionMessageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6190](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6190)

Encodes the specified BotPromotionMessageMetadata message. Does not implicitly [verify](BotPromotionMessageMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

BotPromotionMessageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6198](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6198)

Encodes the specified BotPromotionMessageMetadata message, length delimited. Does not implicitly [verify](BotPromotionMessageMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

BotPromotionMessageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:6231](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6231)

Creates a BotPromotionMessageMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

BotPromotionMessageMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6252](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6252)

Gets the default type url for BotPromotionMessageMetadata

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

Defined in: [WAProto/index.d.ts:6239](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6239)

Creates a plain object from a BotPromotionMessageMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

BotPromotionMessageMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6224](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L6224)

Verifies a BotPromotionMessageMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
