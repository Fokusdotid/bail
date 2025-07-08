# Class: UserStatusMuteAction

Defined in: [WAProto/index.d.ts:49459](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49459)

Represents a UserStatusMuteAction.

## Implements

- [`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

## Constructors

### new UserStatusMuteAction()

> **new UserStatusMuteAction**(`properties`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:49465](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49465)

Constructs a new UserStatusMuteAction.

#### Parameters

##### properties?

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

Properties to set

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

## Properties

### muted?

> `optional` **muted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:49468](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49468)

UserStatusMuteAction muted.

#### Implementation of

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md).[`muted`](../interfaces/IUserStatusMuteAction.md#muted)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:49538](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49538)

Converts this UserStatusMuteAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:49475](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49475)

Creates a new UserStatusMuteAction instance using the specified properties.

#### Parameters

##### properties?

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

Properties to set

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:49501](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49501)

Decodes a UserStatusMuteAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:49510](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49510)

Decodes a UserStatusMuteAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49483](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49483)

Encodes the specified UserStatusMuteAction message. Does not implicitly [verify](UserStatusMuteAction.md#verify) messages.

#### Parameters

##### message

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

UserStatusMuteAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49491](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49491)

Encodes the specified UserStatusMuteAction message, length delimited. Does not implicitly [verify](UserStatusMuteAction.md#verify) messages.

#### Parameters

##### message

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

UserStatusMuteAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:49524](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49524)

Creates a UserStatusMuteAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:49545](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49545)

Gets the default type url for UserStatusMuteAction

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

Defined in: [WAProto/index.d.ts:49532](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49532)

Creates a plain object from a UserStatusMuteAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`UserStatusMuteAction`](UserStatusMuteAction.md)

UserStatusMuteAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:49517](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L49517)

Verifies a UserStatusMuteAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
