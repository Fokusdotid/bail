# Class: RecentEmojiWeightsAction

Defined in: [WAProto/index.d.ts:48286](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48286)

Represents a RecentEmojiWeightsAction.

## Implements

- [`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

## Constructors

### new RecentEmojiWeightsAction()

> **new RecentEmojiWeightsAction**(`properties`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:48292](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48292)

Constructs a new RecentEmojiWeightsAction.

#### Parameters

##### properties?

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

Properties to set

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

## Properties

### weights

> **weights**: [`IRecentEmojiWeight`](../../../interfaces/IRecentEmojiWeight.md)[]

Defined in: [WAProto/index.d.ts:48295](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48295)

RecentEmojiWeightsAction weights.

#### Implementation of

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md).[`weights`](../interfaces/IRecentEmojiWeightsAction.md#weights)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48365](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48365)

Converts this RecentEmojiWeightsAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:48302](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48302)

Creates a new RecentEmojiWeightsAction instance using the specified properties.

#### Parameters

##### properties?

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

Properties to set

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:48328](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48328)

Decodes a RecentEmojiWeightsAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:48337](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48337)

Decodes a RecentEmojiWeightsAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48310](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48310)

Encodes the specified RecentEmojiWeightsAction message. Does not implicitly [verify](RecentEmojiWeightsAction.md#verify) messages.

#### Parameters

##### message

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

RecentEmojiWeightsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48318](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48318)

Encodes the specified RecentEmojiWeightsAction message, length delimited. Does not implicitly [verify](RecentEmojiWeightsAction.md#verify) messages.

#### Parameters

##### message

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

RecentEmojiWeightsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:48351](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48351)

Creates a RecentEmojiWeightsAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48372](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48372)

Gets the default type url for RecentEmojiWeightsAction

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

Defined in: [WAProto/index.d.ts:48359](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48359)

Creates a plain object from a RecentEmojiWeightsAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

RecentEmojiWeightsAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48344](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L48344)

Verifies a RecentEmojiWeightsAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
