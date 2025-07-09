# Class: FavoritesAction

Defined in: [WAProto/index.d.ts:45418](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45418)

Represents a FavoritesAction.

## Implements

- [`IFavoritesAction`](../interfaces/IFavoritesAction.md)

## Constructors

### new FavoritesAction()

> **new FavoritesAction**(`properties`?): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:45424](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45424)

Constructs a new FavoritesAction.

#### Parameters

##### properties?

[`IFavoritesAction`](../interfaces/IFavoritesAction.md)

Properties to set

#### Returns

[`FavoritesAction`](FavoritesAction.md)

## Properties

### favorites

> **favorites**: [`IFavorite`](../namespaces/FavoritesAction/interfaces/IFavorite.md)[]

Defined in: [WAProto/index.d.ts:45427](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45427)

FavoritesAction favorites.

#### Implementation of

[`IFavoritesAction`](../interfaces/IFavoritesAction.md).[`favorites`](../interfaces/IFavoritesAction.md#favorites)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45497](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45497)

Converts this FavoritesAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:45434](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45434)

Creates a new FavoritesAction instance using the specified properties.

#### Parameters

##### properties?

[`IFavoritesAction`](../interfaces/IFavoritesAction.md)

Properties to set

#### Returns

[`FavoritesAction`](FavoritesAction.md)

FavoritesAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:45460](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45460)

Decodes a FavoritesAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`FavoritesAction`](FavoritesAction.md)

FavoritesAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:45469](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45469)

Decodes a FavoritesAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`FavoritesAction`](FavoritesAction.md)

FavoritesAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45442](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45442)

Encodes the specified FavoritesAction message. Does not implicitly [verify](FavoritesAction.md#verify) messages.

#### Parameters

##### message

[`IFavoritesAction`](../interfaces/IFavoritesAction.md)

FavoritesAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45450](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45450)

Encodes the specified FavoritesAction message, length delimited. Does not implicitly [verify](FavoritesAction.md#verify) messages.

#### Parameters

##### message

[`IFavoritesAction`](../interfaces/IFavoritesAction.md)

FavoritesAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:45483](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45483)

Creates a FavoritesAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`FavoritesAction`](FavoritesAction.md)

FavoritesAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45504](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45504)

Gets the default type url for FavoritesAction

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

Defined in: [WAProto/index.d.ts:45491](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45491)

Creates a plain object from a FavoritesAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`FavoritesAction`](FavoritesAction.md)

FavoritesAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:45476](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L45476)

Verifies a FavoritesAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
