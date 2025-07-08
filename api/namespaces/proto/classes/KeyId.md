# Class: KeyId

Defined in: [WAProto/index.d.ts:17048](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17048)

Represents a KeyId.

## Implements

- [`IKeyId`](../interfaces/IKeyId.md)

## Constructors

### new KeyId()

> **new KeyId**(`properties`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:17054](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17054)

Constructs a new KeyId.

#### Parameters

##### properties?

[`IKeyId`](../interfaces/IKeyId.md)

Properties to set

#### Returns

[`KeyId`](KeyId.md)

## Properties

### id?

> `optional` **id**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:17057](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17057)

KeyId id.

#### Implementation of

[`IKeyId`](../interfaces/IKeyId.md).[`id`](../interfaces/IKeyId.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17127](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17127)

Converts this KeyId to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:17064](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17064)

Creates a new KeyId instance using the specified properties.

#### Parameters

##### properties?

[`IKeyId`](../interfaces/IKeyId.md)

Properties to set

#### Returns

[`KeyId`](KeyId.md)

KeyId instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:17090](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17090)

Decodes a KeyId message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeyId`](KeyId.md)

KeyId

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:17099](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17099)

Decodes a KeyId message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeyId`](KeyId.md)

KeyId

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17072](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17072)

Encodes the specified KeyId message. Does not implicitly [verify](KeyId.md#verify) messages.

#### Parameters

##### message

[`IKeyId`](../interfaces/IKeyId.md)

KeyId message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17080](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17080)

Encodes the specified KeyId message, length delimited. Does not implicitly [verify](KeyId.md#verify) messages.

#### Parameters

##### message

[`IKeyId`](../interfaces/IKeyId.md)

KeyId message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:17113](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17113)

Creates a KeyId message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeyId`](KeyId.md)

KeyId

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:17134](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17134)

Gets the default type url for KeyId

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

Defined in: [WAProto/index.d.ts:17121](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17121)

Creates a plain object from a KeyId message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeyId`](KeyId.md)

KeyId

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17106](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L17106)

Verifies a KeyId message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
