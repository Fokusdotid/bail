# Class: PrimaryEphemeralIdentity

Defined in: [WAProto/index.d.ts:39939](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39939)

Represents a PrimaryEphemeralIdentity.

## Implements

- [`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

## Constructors

### new PrimaryEphemeralIdentity()

> **new PrimaryEphemeralIdentity**(`properties`?): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:39945](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39945)

Constructs a new PrimaryEphemeralIdentity.

#### Parameters

##### properties?

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

Properties to set

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

## Properties

### nonce?

> `optional` **nonce**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:39951](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39951)

PrimaryEphemeralIdentity nonce.

#### Implementation of

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md).[`nonce`](../interfaces/IPrimaryEphemeralIdentity.md#nonce)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:39948](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39948)

PrimaryEphemeralIdentity publicKey.

#### Implementation of

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md).[`publicKey`](../interfaces/IPrimaryEphemeralIdentity.md#publickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:40021](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L40021)

Converts this PrimaryEphemeralIdentity to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:39958](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39958)

Creates a new PrimaryEphemeralIdentity instance using the specified properties.

#### Parameters

##### properties?

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

Properties to set

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

PrimaryEphemeralIdentity instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:39984](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39984)

Decodes a PrimaryEphemeralIdentity message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

PrimaryEphemeralIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:39993](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39993)

Decodes a PrimaryEphemeralIdentity message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

PrimaryEphemeralIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39966](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39966)

Encodes the specified PrimaryEphemeralIdentity message. Does not implicitly [verify](PrimaryEphemeralIdentity.md#verify) messages.

#### Parameters

##### message

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

PrimaryEphemeralIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:39974](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L39974)

Encodes the specified PrimaryEphemeralIdentity message, length delimited. Does not implicitly [verify](PrimaryEphemeralIdentity.md#verify) messages.

#### Parameters

##### message

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

PrimaryEphemeralIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:40007](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L40007)

Creates a PrimaryEphemeralIdentity message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

PrimaryEphemeralIdentity

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:40028](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L40028)

Gets the default type url for PrimaryEphemeralIdentity

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

Defined in: [WAProto/index.d.ts:40015](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L40015)

Creates a plain object from a PrimaryEphemeralIdentity message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

PrimaryEphemeralIdentity

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:40000](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L40000)

Verifies a PrimaryEphemeralIdentity message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
