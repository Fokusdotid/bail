# Class: Chat

Defined in: [WAProto/index.d.ts:21357](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21357)

Represents a Chat.

## Implements

- [`IChat`](../interfaces/IChat.md)

## Constructors

### new Chat()

> **new Chat**(`properties`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:21363](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21363)

Constructs a new Chat.

#### Parameters

##### properties?

[`IChat`](../interfaces/IChat.md)

Properties to set

#### Returns

[`Chat`](Chat.md)

## Properties

### displayName?

> `optional` **displayName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21366](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21366)

Chat displayName.

#### Implementation of

[`IChat`](../interfaces/IChat.md).[`displayName`](../interfaces/IChat.md#displayname)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21369](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21369)

Chat id.

#### Implementation of

[`IChat`](../interfaces/IChat.md).[`id`](../interfaces/IChat.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21439](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21439)

Converts this Chat to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:21376](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21376)

Creates a new Chat instance using the specified properties.

#### Parameters

##### properties?

[`IChat`](../interfaces/IChat.md)

Properties to set

#### Returns

[`Chat`](Chat.md)

Chat instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:21402](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21402)

Decodes a Chat message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Chat`](Chat.md)

Chat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:21411](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21411)

Decodes a Chat message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Chat`](Chat.md)

Chat

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21384](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21384)

Encodes the specified Chat message. Does not implicitly [verify](Chat.md#verify) messages.

#### Parameters

##### message

[`IChat`](../interfaces/IChat.md)

Chat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21392](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21392)

Encodes the specified Chat message, length delimited. Does not implicitly [verify](Chat.md#verify) messages.

#### Parameters

##### message

[`IChat`](../interfaces/IChat.md)

Chat message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:21425](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21425)

Creates a Chat message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Chat`](Chat.md)

Chat

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21446](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21446)

Gets the default type url for Chat

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

Defined in: [WAProto/index.d.ts:21433](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21433)

Creates a plain object from a Chat message. Also converts values to other types if specified.

#### Parameters

##### message

[`Chat`](Chat.md)

Chat

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21418](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L21418)

Verifies a Chat message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
