# Class: LocalizedName

Defined in: [WAProto/index.d.ts:17689](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17689)

Represents a LocalizedName.

## Implements

- [`ILocalizedName`](../interfaces/ILocalizedName.md)

## Constructors

### new LocalizedName()

> **new LocalizedName**(`properties`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:17695](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17695)

Constructs a new LocalizedName.

#### Parameters

##### properties?

[`ILocalizedName`](../interfaces/ILocalizedName.md)

Properties to set

#### Returns

[`LocalizedName`](LocalizedName.md)

## Properties

### lc?

> `optional` **lc**: `null` \| `string`

Defined in: [WAProto/index.d.ts:17701](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17701)

LocalizedName lc.

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`lc`](../interfaces/ILocalizedName.md#lc)

***

### lg?

> `optional` **lg**: `null` \| `string`

Defined in: [WAProto/index.d.ts:17698](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17698)

LocalizedName lg.

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`lg`](../interfaces/ILocalizedName.md#lg)

***

### verifiedName?

> `optional` **verifiedName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:17704](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17704)

LocalizedName verifiedName.

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`verifiedName`](../interfaces/ILocalizedName.md#verifiedname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17774](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17774)

Converts this LocalizedName to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:17711](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17711)

Creates a new LocalizedName instance using the specified properties.

#### Parameters

##### properties?

[`ILocalizedName`](../interfaces/ILocalizedName.md)

Properties to set

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:17737](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17737)

Decodes a LocalizedName message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:17746](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17746)

Decodes a LocalizedName message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17719](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17719)

Encodes the specified LocalizedName message. Does not implicitly [verify](LocalizedName.md#verify) messages.

#### Parameters

##### message

[`ILocalizedName`](../interfaces/ILocalizedName.md)

LocalizedName message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17727](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17727)

Encodes the specified LocalizedName message, length delimited. Does not implicitly [verify](LocalizedName.md#verify) messages.

#### Parameters

##### message

[`ILocalizedName`](../interfaces/ILocalizedName.md)

LocalizedName message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:17760](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17760)

Creates a LocalizedName message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LocalizedName`](LocalizedName.md)

LocalizedName

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:17781](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17781)

Gets the default type url for LocalizedName

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

Defined in: [WAProto/index.d.ts:17768](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17768)

Creates a plain object from a LocalizedName message. Also converts values to other types if specified.

#### Parameters

##### message

[`LocalizedName`](LocalizedName.md)

LocalizedName

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17753](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17753)

Verifies a LocalizedName message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
