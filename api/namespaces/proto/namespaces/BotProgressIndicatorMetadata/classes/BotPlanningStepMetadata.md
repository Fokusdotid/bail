# Class: BotPlanningStepMetadata

Defined in: [WAProto/index.d.ts:5681](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5681)

Represents a BotPlanningStepMetadata.

## Implements

- [`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

## Constructors

### new BotPlanningStepMetadata()

> **new BotPlanningStepMetadata**(`properties`?): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:5687](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5687)

Constructs a new BotPlanningStepMetadata.

#### Parameters

##### properties?

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

Properties to set

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

## Properties

### isEnhancedSearch?

> `optional` **isEnhancedSearch**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:5705](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5705)

BotPlanningStepMetadata isEnhancedSearch.

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`isEnhancedSearch`](../interfaces/IBotPlanningStepMetadata.md#isenhancedsearch)

***

### isReasoning?

> `optional` **isReasoning**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:5702](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5702)

BotPlanningStepMetadata isReasoning.

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`isReasoning`](../interfaces/IBotPlanningStepMetadata.md#isreasoning)

***

### sections

> **sections**: [`IBotPlanningStepSectionMetadata`](../namespaces/BotPlanningStepMetadata/interfaces/IBotPlanningStepSectionMetadata.md)[]

Defined in: [WAProto/index.d.ts:5708](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5708)

BotPlanningStepMetadata sections.

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`sections`](../interfaces/IBotPlanningStepMetadata.md#sections)

***

### sourcesMetadata

> **sourcesMetadata**: [`IBotPlanningSearchSourcesMetadata`](../namespaces/BotPlanningStepMetadata/interfaces/IBotPlanningSearchSourcesMetadata.md)[]

Defined in: [WAProto/index.d.ts:5696](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5696)

BotPlanningStepMetadata sourcesMetadata.

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`sourcesMetadata`](../interfaces/IBotPlanningStepMetadata.md#sourcesmetadata)

***

### status?

> `optional` **status**: `null` \| [`PlanningStepStatus`](../namespaces/BotPlanningStepMetadata/enumerations/PlanningStepStatus.md)

Defined in: [WAProto/index.d.ts:5699](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5699)

BotPlanningStepMetadata status.

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`status`](../interfaces/IBotPlanningStepMetadata.md#status)

***

### statusBody?

> `optional` **statusBody**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5693](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5693)

BotPlanningStepMetadata statusBody.

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`statusBody`](../interfaces/IBotPlanningStepMetadata.md#statusbody)

***

### statusTitle?

> `optional` **statusTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5690](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5690)

BotPlanningStepMetadata statusTitle.

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`statusTitle`](../interfaces/IBotPlanningStepMetadata.md#statustitle)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5778](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5778)

Converts this BotPlanningStepMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:5715](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5715)

Creates a new BotPlanningStepMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

Properties to set

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

BotPlanningStepMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:5741](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5741)

Decodes a BotPlanningStepMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

BotPlanningStepMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:5750](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5750)

Decodes a BotPlanningStepMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

BotPlanningStepMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5723](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5723)

Encodes the specified BotPlanningStepMetadata message. Does not implicitly [verify](BotPlanningStepMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

BotPlanningStepMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5731](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5731)

Encodes the specified BotPlanningStepMetadata message, length delimited. Does not implicitly [verify](BotPlanningStepMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

BotPlanningStepMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:5764](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5764)

Creates a BotPlanningStepMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

BotPlanningStepMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5785](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5785)

Gets the default type url for BotPlanningStepMetadata

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

Defined in: [WAProto/index.d.ts:5772](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5772)

Creates a plain object from a BotPlanningStepMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

BotPlanningStepMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5757](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L5757)

Verifies a BotPlanningStepMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
