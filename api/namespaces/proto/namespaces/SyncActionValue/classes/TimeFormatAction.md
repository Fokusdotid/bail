# Class: TimeFormatAction

Defined in: [WAProto/index.d.ts:49265](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49265)

Represents a TimeFormatAction.

## Implements

- [`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

## Constructors

### new TimeFormatAction()

> **new TimeFormatAction**(`properties`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:49271](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49271)

Constructs a new TimeFormatAction.

#### Parameters

##### properties?

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

Properties to set

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

## Properties

### isTwentyFourHourFormatEnabled?

> `optional` **isTwentyFourHourFormatEnabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:49274](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49274)

TimeFormatAction isTwentyFourHourFormatEnabled.

#### Implementation of

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md).[`isTwentyFourHourFormatEnabled`](../interfaces/ITimeFormatAction.md#istwentyfourhourformatenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:49344](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49344)

Converts this TimeFormatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:49281](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49281)

Creates a new TimeFormatAction instance using the specified properties.

#### Parameters

##### properties?

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

Properties to set

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:49307](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49307)

Decodes a TimeFormatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:49316](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49316)

Decodes a TimeFormatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49289](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49289)

Encodes the specified TimeFormatAction message. Does not implicitly [verify](TimeFormatAction.md#verify) messages.

#### Parameters

##### message

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

TimeFormatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49297](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49297)

Encodes the specified TimeFormatAction message, length delimited. Does not implicitly [verify](TimeFormatAction.md#verify) messages.

#### Parameters

##### message

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

TimeFormatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:49330](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49330)

Creates a TimeFormatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:49351](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49351)

Gets the default type url for TimeFormatAction

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

Defined in: [WAProto/index.d.ts:49338](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49338)

Creates a plain object from a TimeFormatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`TimeFormatAction`](TimeFormatAction.md)

TimeFormatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:49323](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L49323)

Verifies a TimeFormatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
