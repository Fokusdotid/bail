# Class: Point

Defined in: [WAProto/index.d.ts:39176](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39176)

Represents a Point.

## Implements

- [`IPoint`](../interfaces/IPoint.md)

## Constructors

### new Point()

> **new Point**(`properties`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:39182](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39182)

Constructs a new Point.

#### Parameters

##### properties?

[`IPoint`](../interfaces/IPoint.md)

Properties to set

#### Returns

[`Point`](Point.md)

## Properties

### x?

> `optional` **x**: `null` \| `number`

Defined in: [WAProto/index.d.ts:39191](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39191)

Point x.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`x`](../interfaces/IPoint.md#x)

***

### xDeprecated?

> `optional` **xDeprecated**: `null` \| `number`

Defined in: [WAProto/index.d.ts:39185](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39185)

Point xDeprecated.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`xDeprecated`](../interfaces/IPoint.md#xdeprecated)

***

### y?

> `optional` **y**: `null` \| `number`

Defined in: [WAProto/index.d.ts:39194](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39194)

Point y.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`y`](../interfaces/IPoint.md#y)

***

### yDeprecated?

> `optional` **yDeprecated**: `null` \| `number`

Defined in: [WAProto/index.d.ts:39188](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39188)

Point yDeprecated.

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`yDeprecated`](../interfaces/IPoint.md#ydeprecated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:39264](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39264)

Converts this Point to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:39201](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39201)

Creates a new Point instance using the specified properties.

#### Parameters

##### properties?

[`IPoint`](../interfaces/IPoint.md)

Properties to set

#### Returns

[`Point`](Point.md)

Point instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:39227](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39227)

Decodes a Point message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Point`](Point.md)

Point

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:39236](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39236)

Decodes a Point message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Point`](Point.md)

Point

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39209](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39209)

Encodes the specified Point message. Does not implicitly [verify](Point.md#verify) messages.

#### Parameters

##### message

[`IPoint`](../interfaces/IPoint.md)

Point message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39217](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39217)

Encodes the specified Point message, length delimited. Does not implicitly [verify](Point.md#verify) messages.

#### Parameters

##### message

[`IPoint`](../interfaces/IPoint.md)

Point message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:39250](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39250)

Creates a Point message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Point`](Point.md)

Point

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:39271](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39271)

Gets the default type url for Point

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

Defined in: [WAProto/index.d.ts:39258](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39258)

Creates a plain object from a Point message. Also converts values to other types if specified.

#### Parameters

##### message

[`Point`](Point.md)

Point

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:39243](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L39243)

Verifies a Point message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
