# Class: CollectionMessage

Defined in: [WAProto/index.d.ts:25311](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25311)

Represents a CollectionMessage.

## Implements

- [`ICollectionMessage`](../interfaces/ICollectionMessage.md)

## Constructors

### new CollectionMessage()

> **new CollectionMessage**(`properties`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:25317](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25317)

Constructs a new CollectionMessage.

#### Parameters

##### properties?

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

Properties to set

#### Returns

[`CollectionMessage`](CollectionMessage.md)

## Properties

### bizJid?

> `optional` **bizJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25320](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25320)

CollectionMessage bizJid.

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`bizJid`](../interfaces/ICollectionMessage.md#bizjid)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25323](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25323)

CollectionMessage id.

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`id`](../interfaces/ICollectionMessage.md#id)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:25326](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25326)

CollectionMessage messageVersion.

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`messageVersion`](../interfaces/ICollectionMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25396](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25396)

Converts this CollectionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:25333](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25333)

Creates a new CollectionMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

Properties to set

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:25359](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25359)

Decodes a CollectionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:25368](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25368)

Decodes a CollectionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25341](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25341)

Encodes the specified CollectionMessage message. Does not implicitly [verify](CollectionMessage.md#verify) messages.

#### Parameters

##### message

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

CollectionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25349](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25349)

Encodes the specified CollectionMessage message, length delimited. Does not implicitly [verify](CollectionMessage.md#verify) messages.

#### Parameters

##### message

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

CollectionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:25382](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25382)

Creates a CollectionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:25403](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25403)

Gets the default type url for CollectionMessage

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

Defined in: [WAProto/index.d.ts:25390](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25390)

Creates a plain object from a CollectionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CollectionMessage`](CollectionMessage.md)

CollectionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25375](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L25375)

Verifies a CollectionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
