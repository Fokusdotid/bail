# Class: MarketingMessageAction

Defined in: [WAProto/index.d.ts:46490](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46490)

Represents a MarketingMessageAction.

## Implements

- [`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

## Constructors

### new MarketingMessageAction()

> **new MarketingMessageAction**(`properties`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:46496](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46496)

Constructs a new MarketingMessageAction.

#### Parameters

##### properties?

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

Properties to set

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

## Properties

### createdAt?

> `optional` **createdAt**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:46508](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46508)

MarketingMessageAction createdAt.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`createdAt`](../interfaces/IMarketingMessageAction.md#createdat)

***

### isDeleted?

> `optional` **isDeleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:46514](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46514)

MarketingMessageAction isDeleted.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`isDeleted`](../interfaces/IMarketingMessageAction.md#isdeleted)

***

### lastSentAt?

> `optional` **lastSentAt**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:46511](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46511)

MarketingMessageAction lastSentAt.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`lastSentAt`](../interfaces/IMarketingMessageAction.md#lastsentat)

***

### mediaId?

> `optional` **mediaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46517](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46517)

MarketingMessageAction mediaId.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`mediaId`](../interfaces/IMarketingMessageAction.md#mediaid)

***

### message?

> `optional` **message**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46502](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46502)

MarketingMessageAction message.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`message`](../interfaces/IMarketingMessageAction.md#message)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46499](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46499)

MarketingMessageAction name.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`name`](../interfaces/IMarketingMessageAction.md#name)

***

### type?

> `optional` **type**: `null` \| [`PERSONALIZED`](../namespaces/MarketingMessageAction/enumerations/MarketingMessagePrototypeType.md#personalized)

Defined in: [WAProto/index.d.ts:46505](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46505)

MarketingMessageAction type.

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`type`](../interfaces/IMarketingMessageAction.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:46587](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46587)

Converts this MarketingMessageAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:46524](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46524)

Creates a new MarketingMessageAction instance using the specified properties.

#### Parameters

##### properties?

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

Properties to set

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:46550](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46550)

Decodes a MarketingMessageAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:46559](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46559)

Decodes a MarketingMessageAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46532](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46532)

Encodes the specified MarketingMessageAction message. Does not implicitly [verify](MarketingMessageAction.md#verify) messages.

#### Parameters

##### message

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

MarketingMessageAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46540](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46540)

Encodes the specified MarketingMessageAction message, length delimited. Does not implicitly [verify](MarketingMessageAction.md#verify) messages.

#### Parameters

##### message

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

MarketingMessageAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:46573](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46573)

Creates a MarketingMessageAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:46594](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46594)

Gets the default type url for MarketingMessageAction

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

Defined in: [WAProto/index.d.ts:46581](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46581)

Creates a plain object from a MarketingMessageAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`MarketingMessageAction`](MarketingMessageAction.md)

MarketingMessageAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:46566](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L46566)

Verifies a MarketingMessageAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
