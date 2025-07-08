# Class: Favorite

Defined in: [WAProto/index.d.ts:45517](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45517)

Represents a Favorite.

## Implements

- [`IFavorite`](../interfaces/IFavorite.md)

## Constructors

### new Favorite()

> **new Favorite**(`properties`?): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:45523](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45523)

Constructs a new Favorite.

#### Parameters

##### properties?

[`IFavorite`](../interfaces/IFavorite.md)

Properties to set

#### Returns

[`Favorite`](Favorite.md)

## Properties

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:45526](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45526)

Favorite id.

#### Implementation of

[`IFavorite`](../interfaces/IFavorite.md).[`id`](../interfaces/IFavorite.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45596](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45596)

Converts this Favorite to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:45533](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45533)

Creates a new Favorite instance using the specified properties.

#### Parameters

##### properties?

[`IFavorite`](../interfaces/IFavorite.md)

Properties to set

#### Returns

[`Favorite`](Favorite.md)

Favorite instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:45559](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45559)

Decodes a Favorite message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Favorite`](Favorite.md)

Favorite

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:45568](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45568)

Decodes a Favorite message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Favorite`](Favorite.md)

Favorite

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45541](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45541)

Encodes the specified Favorite message. Does not implicitly [verify](Favorite.md#verify) messages.

#### Parameters

##### message

[`IFavorite`](../interfaces/IFavorite.md)

Favorite message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45549](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45549)

Encodes the specified Favorite message, length delimited. Does not implicitly [verify](Favorite.md#verify) messages.

#### Parameters

##### message

[`IFavorite`](../interfaces/IFavorite.md)

Favorite message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:45582](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45582)

Creates a Favorite message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Favorite`](Favorite.md)

Favorite

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45603](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45603)

Gets the default type url for Favorite

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

Defined in: [WAProto/index.d.ts:45590](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45590)

Creates a plain object from a Favorite message. Also converts values to other types if specified.

#### Parameters

##### message

[`Favorite`](Favorite.md)

Favorite

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:45575](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45575)

Verifies a Favorite message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
