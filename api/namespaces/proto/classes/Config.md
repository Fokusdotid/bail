# Class: Config

Defined in: [WAProto/index.d.ts:10645](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10645)

Represents a Config.

## Implements

- [`IConfig`](../interfaces/IConfig.md)

## Constructors

### new Config()

> **new Config**(`properties`?): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:10651](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10651)

Constructs a new Config.

#### Parameters

##### properties?

[`IConfig`](../interfaces/IConfig.md)

Properties to set

#### Returns

[`Config`](Config.md)

## Properties

### field

> **field**: `object`

Defined in: [WAProto/index.d.ts:10654](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10654)

Config field.

#### Index Signature

\[`k`: `string`\]: [`IField`](../interfaces/IField.md)

#### Implementation of

[`IConfig`](../interfaces/IConfig.md).[`field`](../interfaces/IConfig.md#field)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10657](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10657)

Config version.

#### Implementation of

[`IConfig`](../interfaces/IConfig.md).[`version`](../interfaces/IConfig.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10727](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10727)

Converts this Config to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:10664](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10664)

Creates a new Config instance using the specified properties.

#### Parameters

##### properties?

[`IConfig`](../interfaces/IConfig.md)

Properties to set

#### Returns

[`Config`](Config.md)

Config instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:10690](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10690)

Decodes a Config message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Config`](Config.md)

Config

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:10699](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10699)

Decodes a Config message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Config`](Config.md)

Config

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10672](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10672)

Encodes the specified Config message. Does not implicitly [verify](Config.md#verify) messages.

#### Parameters

##### message

[`IConfig`](../interfaces/IConfig.md)

Config message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10680](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10680)

Encodes the specified Config message, length delimited. Does not implicitly [verify](Config.md#verify) messages.

#### Parameters

##### message

[`IConfig`](../interfaces/IConfig.md)

Config message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:10713](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10713)

Creates a Config message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Config`](Config.md)

Config

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10734](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10734)

Gets the default type url for Config

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

Defined in: [WAProto/index.d.ts:10721](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10721)

Creates a plain object from a Config message. Also converts values to other types if specified.

#### Parameters

##### message

[`Config`](Config.md)

Config

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10706](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L10706)

Verifies a Config message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
