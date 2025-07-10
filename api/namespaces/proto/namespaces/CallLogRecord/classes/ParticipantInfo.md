# Class: ParticipantInfo

Defined in: [WAProto/index.d.ts:7709](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7709)

Represents a ParticipantInfo.

## Implements

- [`IParticipantInfo`](../interfaces/IParticipantInfo.md)

## Constructors

### new ParticipantInfo()

> **new ParticipantInfo**(`properties`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:7715](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7715)

Constructs a new ParticipantInfo.

#### Parameters

##### properties?

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

Properties to set

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

## Properties

### callResult?

> `optional` **callResult**: `null` \| [`CallResult`](../enumerations/CallResult.md)

Defined in: [WAProto/index.d.ts:7721](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7721)

ParticipantInfo callResult.

#### Implementation of

[`IParticipantInfo`](../interfaces/IParticipantInfo.md).[`callResult`](../interfaces/IParticipantInfo.md#callresult)

***

### userJid?

> `optional` **userJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7718](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7718)

ParticipantInfo userJid.

#### Implementation of

[`IParticipantInfo`](../interfaces/IParticipantInfo.md).[`userJid`](../interfaces/IParticipantInfo.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7791](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7791)

Converts this ParticipantInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:7728](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7728)

Creates a new ParticipantInfo instance using the specified properties.

#### Parameters

##### properties?

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

Properties to set

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:7754](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7754)

Decodes a ParticipantInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:7763](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7763)

Decodes a ParticipantInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7736](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7736)

Encodes the specified ParticipantInfo message. Does not implicitly [verify](ParticipantInfo.md#verify) messages.

#### Parameters

##### message

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

ParticipantInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7744](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7744)

Encodes the specified ParticipantInfo message, length delimited. Does not implicitly [verify](ParticipantInfo.md#verify) messages.

#### Parameters

##### message

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

ParticipantInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:7777](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7777)

Creates a ParticipantInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7798](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7798)

Gets the default type url for ParticipantInfo

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

Defined in: [WAProto/index.d.ts:7785](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7785)

Creates a plain object from a ParticipantInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ParticipantInfo`](ParticipantInfo.md)

ParticipantInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7770](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L7770)

Verifies a ParticipantInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
