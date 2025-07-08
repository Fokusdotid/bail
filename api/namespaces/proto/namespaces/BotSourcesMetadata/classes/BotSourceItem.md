# Class: BotSourceItem

Defined in: [WAProto/index.d.ts:7262](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7262)

Represents a BotSourceItem.

## Implements

- [`IBotSourceItem`](../interfaces/IBotSourceItem.md)

## Constructors

### new BotSourceItem()

> **new BotSourceItem**(`properties`?): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:7268](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7268)

Constructs a new BotSourceItem.

#### Parameters

##### properties?

[`IBotSourceItem`](../interfaces/IBotSourceItem.md)

Properties to set

#### Returns

[`BotSourceItem`](BotSourceItem.md)

## Properties

### citationNumber?

> `optional` **citationNumber**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7286](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7286)

BotSourceItem citationNumber.

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`citationNumber`](../interfaces/IBotSourceItem.md#citationnumber)

***

### faviconCdnUrl?

> `optional` **faviconCdnUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7283](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7283)

BotSourceItem faviconCdnUrl.

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`faviconCdnUrl`](../interfaces/IBotSourceItem.md#faviconcdnurl)

***

### provider?

> `optional` **provider**: `null` \| [`SourceProvider`](../namespaces/BotSourceItem/enumerations/SourceProvider.md)

Defined in: [WAProto/index.d.ts:7271](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7271)

BotSourceItem provider.

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`provider`](../interfaces/IBotSourceItem.md#provider)

***

### sourceProviderUrl?

> `optional` **sourceProviderUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7277](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7277)

BotSourceItem sourceProviderUrl.

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`sourceProviderUrl`](../interfaces/IBotSourceItem.md#sourceproviderurl)

***

### sourceQuery?

> `optional` **sourceQuery**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7280](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7280)

BotSourceItem sourceQuery.

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`sourceQuery`](../interfaces/IBotSourceItem.md#sourcequery)

***

### thumbnailCdnUrl?

> `optional` **thumbnailCdnUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7274](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7274)

BotSourceItem thumbnailCdnUrl.

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`thumbnailCdnUrl`](../interfaces/IBotSourceItem.md#thumbnailcdnurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7356](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7356)

Converts this BotSourceItem to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:7293](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7293)

Creates a new BotSourceItem instance using the specified properties.

#### Parameters

##### properties?

[`IBotSourceItem`](../interfaces/IBotSourceItem.md)

Properties to set

#### Returns

[`BotSourceItem`](BotSourceItem.md)

BotSourceItem instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:7319](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7319)

Decodes a BotSourceItem message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotSourceItem`](BotSourceItem.md)

BotSourceItem

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:7328](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7328)

Decodes a BotSourceItem message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotSourceItem`](BotSourceItem.md)

BotSourceItem

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7301](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7301)

Encodes the specified BotSourceItem message. Does not implicitly [verify](BotSourceItem.md#verify) messages.

#### Parameters

##### message

[`IBotSourceItem`](../interfaces/IBotSourceItem.md)

BotSourceItem message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7309](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7309)

Encodes the specified BotSourceItem message, length delimited. Does not implicitly [verify](BotSourceItem.md#verify) messages.

#### Parameters

##### message

[`IBotSourceItem`](../interfaces/IBotSourceItem.md)

BotSourceItem message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:7342](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7342)

Creates a BotSourceItem message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotSourceItem`](BotSourceItem.md)

BotSourceItem

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7363](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7363)

Gets the default type url for BotSourceItem

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

Defined in: [WAProto/index.d.ts:7350](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7350)

Creates a plain object from a BotSourceItem message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotSourceItem`](BotSourceItem.md)

BotSourceItem

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7335](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L7335)

Verifies a BotSourceItem message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
