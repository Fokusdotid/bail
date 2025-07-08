# Class: Money

Defined in: [WAProto/index.d.ts:36370](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36370)

Represents a Money.

## Implements

- [`IMoney`](../interfaces/IMoney.md)

## Constructors

### new Money()

> **new Money**(`properties`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:36376](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36376)

Constructs a new Money.

#### Parameters

##### properties?

[`IMoney`](../interfaces/IMoney.md)

Properties to set

#### Returns

[`Money`](Money.md)

## Properties

### currencyCode?

> `optional` **currencyCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:36385](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36385)

Money currencyCode.

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`currencyCode`](../interfaces/IMoney.md#currencycode)

***

### offset?

> `optional` **offset**: `null` \| `number`

Defined in: [WAProto/index.d.ts:36382](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36382)

Money offset.

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`offset`](../interfaces/IMoney.md#offset)

***

### value?

> `optional` **value**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:36379](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36379)

Money value.

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`value`](../interfaces/IMoney.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:36455](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36455)

Converts this Money to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:36392](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36392)

Creates a new Money instance using the specified properties.

#### Parameters

##### properties?

[`IMoney`](../interfaces/IMoney.md)

Properties to set

#### Returns

[`Money`](Money.md)

Money instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:36418](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36418)

Decodes a Money message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Money`](Money.md)

Money

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:36427](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36427)

Decodes a Money message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Money`](Money.md)

Money

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36400](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36400)

Encodes the specified Money message. Does not implicitly [verify](Money.md#verify) messages.

#### Parameters

##### message

[`IMoney`](../interfaces/IMoney.md)

Money message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:36408](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36408)

Encodes the specified Money message, length delimited. Does not implicitly [verify](Money.md#verify) messages.

#### Parameters

##### message

[`IMoney`](../interfaces/IMoney.md)

Money message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:36441](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36441)

Creates a Money message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Money`](Money.md)

Money

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:36462](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36462)

Gets the default type url for Money

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

Defined in: [WAProto/index.d.ts:36449](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36449)

Creates a plain object from a Money message. Also converts values to other types if specified.

#### Parameters

##### message

[`Money`](Money.md)

Money

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:36434](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L36434)

Verifies a Money message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
