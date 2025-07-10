# Class: Chain

Defined in: [WAProto/index.d.ts:41966](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41966)

Represents a Chain.

## Implements

- [`IChain`](../interfaces/IChain.md)

## Constructors

### new Chain()

> **new Chain**(`properties`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:41972](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41972)

Constructs a new Chain.

#### Parameters

##### properties?

[`IChain`](../interfaces/IChain.md)

Properties to set

#### Returns

[`Chain`](Chain.md)

## Properties

### chainKey?

> `optional` **chainKey**: `null` \| [`IChainKey`](../namespaces/Chain/interfaces/IChainKey.md)

Defined in: [WAProto/index.d.ts:41981](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41981)

Chain chainKey.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`chainKey`](../interfaces/IChain.md#chainkey)

***

### messageKeys

> **messageKeys**: [`IMessageKey`](../namespaces/Chain/interfaces/IMessageKey.md)[]

Defined in: [WAProto/index.d.ts:41984](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41984)

Chain messageKeys.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`messageKeys`](../interfaces/IChain.md#messagekeys)

***

### senderRatchetKey?

> `optional` **senderRatchetKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41975](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41975)

Chain senderRatchetKey.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`senderRatchetKey`](../interfaces/IChain.md#senderratchetkey)

***

### senderRatchetKeyPrivate?

> `optional` **senderRatchetKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:41978](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41978)

Chain senderRatchetKeyPrivate.

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`senderRatchetKeyPrivate`](../interfaces/IChain.md#senderratchetkeyprivate)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:42054](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42054)

Converts this Chain to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:41991](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41991)

Creates a new Chain instance using the specified properties.

#### Parameters

##### properties?

[`IChain`](../interfaces/IChain.md)

Properties to set

#### Returns

[`Chain`](Chain.md)

Chain instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:42017](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42017)

Decodes a Chain message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Chain`](Chain.md)

Chain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:42026](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42026)

Decodes a Chain message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Chain`](Chain.md)

Chain

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:41999](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L41999)

Encodes the specified Chain message. Does not implicitly [verify](Chain.md#verify) messages.

#### Parameters

##### message

[`IChain`](../interfaces/IChain.md)

Chain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42007](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42007)

Encodes the specified Chain message, length delimited. Does not implicitly [verify](Chain.md#verify) messages.

#### Parameters

##### message

[`IChain`](../interfaces/IChain.md)

Chain message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:42040](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42040)

Creates a Chain message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Chain`](Chain.md)

Chain

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:42061](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42061)

Gets the default type url for Chain

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

Defined in: [WAProto/index.d.ts:42048](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42048)

Creates a plain object from a Chain message. Also converts values to other types if specified.

#### Parameters

##### message

[`Chain`](Chain.md)

Chain

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:42033](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L42033)

Verifies a Chain message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
