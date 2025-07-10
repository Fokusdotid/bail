# Class: BotWelcomeRequestAction

Defined in: [WAProto/index.d.ts:43994](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L43994)

Represents a BotWelcomeRequestAction.

## Implements

- [`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

## Constructors

### new BotWelcomeRequestAction()

> **new BotWelcomeRequestAction**(`properties`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:44000](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44000)

Constructs a new BotWelcomeRequestAction.

#### Parameters

##### properties?

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

Properties to set

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

## Properties

### isSent?

> `optional` **isSent**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:44003](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44003)

BotWelcomeRequestAction isSent.

#### Implementation of

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md).[`isSent`](../interfaces/IBotWelcomeRequestAction.md#issent)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:44073](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44073)

Converts this BotWelcomeRequestAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:44010](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44010)

Creates a new BotWelcomeRequestAction instance using the specified properties.

#### Parameters

##### properties?

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

Properties to set

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:44036](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44036)

Decodes a BotWelcomeRequestAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:44045](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44045)

Decodes a BotWelcomeRequestAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44018](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44018)

Encodes the specified BotWelcomeRequestAction message. Does not implicitly [verify](BotWelcomeRequestAction.md#verify) messages.

#### Parameters

##### message

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

BotWelcomeRequestAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44026](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44026)

Encodes the specified BotWelcomeRequestAction message, length delimited. Does not implicitly [verify](BotWelcomeRequestAction.md#verify) messages.

#### Parameters

##### message

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

BotWelcomeRequestAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:44059](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44059)

Creates a BotWelcomeRequestAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:44080](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44080)

Gets the default type url for BotWelcomeRequestAction

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

Defined in: [WAProto/index.d.ts:44067](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44067)

Creates a plain object from a BotWelcomeRequestAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

BotWelcomeRequestAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44052](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L44052)

Verifies a BotWelcomeRequestAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
