# Class: ChainKey

Defined in: [WAProto/index.d.ts:42077](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42077)

Represents a ChainKey.

## Implements

- [`IChainKey`](../interfaces/IChainKey.md)

## Constructors

### new ChainKey()

> **new ChainKey**(`properties`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:42083](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42083)

Constructs a new ChainKey.

#### Parameters

##### properties?

[`IChainKey`](../interfaces/IChainKey.md)

Properties to set

#### Returns

[`ChainKey`](ChainKey.md)

## Properties

### index?

> `optional` **index**: `null` \| `number`

Defined in: [WAProto/index.d.ts:42086](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42086)

ChainKey index.

#### Implementation of

[`IChainKey`](../interfaces/IChainKey.md).[`index`](../interfaces/IChainKey.md#index)

***

### key?

> `optional` **key**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42089](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42089)

ChainKey key.

#### Implementation of

[`IChainKey`](../interfaces/IChainKey.md).[`key`](../interfaces/IChainKey.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:42159](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42159)

Converts this ChainKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:42096](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42096)

Creates a new ChainKey instance using the specified properties.

#### Parameters

##### properties?

[`IChainKey`](../interfaces/IChainKey.md)

Properties to set

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:42122](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42122)

Decodes a ChainKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:42131](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42131)

Decodes a ChainKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42104](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42104)

Encodes the specified ChainKey message. Does not implicitly [verify](ChainKey.md#verify) messages.

#### Parameters

##### message

[`IChainKey`](../interfaces/IChainKey.md)

ChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42112](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42112)

Encodes the specified ChainKey message, length delimited. Does not implicitly [verify](ChainKey.md#verify) messages.

#### Parameters

##### message

[`IChainKey`](../interfaces/IChainKey.md)

ChainKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:42145](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42145)

Creates a ChainKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ChainKey`](ChainKey.md)

ChainKey

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:42166](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42166)

Gets the default type url for ChainKey

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

Defined in: [WAProto/index.d.ts:42153](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42153)

Creates a plain object from a ChainKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`ChainKey`](ChainKey.md)

ChainKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:42138](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42138)

Verifies a ChainKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
