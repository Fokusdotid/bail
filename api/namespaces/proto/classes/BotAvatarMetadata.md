# Class: BotAvatarMetadata

Defined in: [WAProto/index.d.ts:3747](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3747)

Represents a BotAvatarMetadata.

## Implements

- [`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

## Constructors

### new BotAvatarMetadata()

> **new BotAvatarMetadata**(`properties`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:3753](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3753)

Constructs a new BotAvatarMetadata.

#### Parameters

##### properties?

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

Properties to set

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

## Properties

### action?

> `optional` **action**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3762](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3762)

BotAvatarMetadata action.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`action`](../interfaces/IBotAvatarMetadata.md#action)

***

### behaviorGraph?

> `optional` **behaviorGraph**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3759](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3759)

BotAvatarMetadata behaviorGraph.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`behaviorGraph`](../interfaces/IBotAvatarMetadata.md#behaviorgraph)

***

### intensity?

> `optional` **intensity**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3765](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3765)

BotAvatarMetadata intensity.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`intensity`](../interfaces/IBotAvatarMetadata.md#intensity)

***

### sentiment?

> `optional` **sentiment**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3756](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3756)

BotAvatarMetadata sentiment.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`sentiment`](../interfaces/IBotAvatarMetadata.md#sentiment)

***

### wordCount?

> `optional` **wordCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3768](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3768)

BotAvatarMetadata wordCount.

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`wordCount`](../interfaces/IBotAvatarMetadata.md#wordcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3838](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3838)

Converts this BotAvatarMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:3775](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3775)

Creates a new BotAvatarMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

Properties to set

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:3801](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3801)

Decodes a BotAvatarMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:3810](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3810)

Decodes a BotAvatarMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3783](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3783)

Encodes the specified BotAvatarMetadata message. Does not implicitly [verify](BotAvatarMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

BotAvatarMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3791](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3791)

Encodes the specified BotAvatarMetadata message, length delimited. Does not implicitly [verify](BotAvatarMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

BotAvatarMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:3824](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3824)

Creates a BotAvatarMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3845](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3845)

Gets the default type url for BotAvatarMetadata

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

Defined in: [WAProto/index.d.ts:3832](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3832)

Creates a plain object from a BotAvatarMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotAvatarMetadata`](BotAvatarMetadata.md)

BotAvatarMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3817](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L3817)

Verifies a BotAvatarMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
