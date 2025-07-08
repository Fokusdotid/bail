# Class: LockChatAction

Defined in: [WAProto/index.d.ts:46272](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46272)

Represents a LockChatAction.

## Implements

- [`ILockChatAction`](../interfaces/ILockChatAction.md)

## Constructors

### new LockChatAction()

> **new LockChatAction**(`properties`?): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:46278](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46278)

Constructs a new LockChatAction.

#### Parameters

##### properties?

[`ILockChatAction`](../interfaces/ILockChatAction.md)

Properties to set

#### Returns

[`LockChatAction`](LockChatAction.md)

## Properties

### locked?

> `optional` **locked**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:46281](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46281)

LockChatAction locked.

#### Implementation of

[`ILockChatAction`](../interfaces/ILockChatAction.md).[`locked`](../interfaces/ILockChatAction.md#locked)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:46351](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46351)

Converts this LockChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:46288](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46288)

Creates a new LockChatAction instance using the specified properties.

#### Parameters

##### properties?

[`ILockChatAction`](../interfaces/ILockChatAction.md)

Properties to set

#### Returns

[`LockChatAction`](LockChatAction.md)

LockChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:46314](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46314)

Decodes a LockChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LockChatAction`](LockChatAction.md)

LockChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:46323](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46323)

Decodes a LockChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LockChatAction`](LockChatAction.md)

LockChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46296](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46296)

Encodes the specified LockChatAction message. Does not implicitly [verify](LockChatAction.md#verify) messages.

#### Parameters

##### message

[`ILockChatAction`](../interfaces/ILockChatAction.md)

LockChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46304](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46304)

Encodes the specified LockChatAction message, length delimited. Does not implicitly [verify](LockChatAction.md#verify) messages.

#### Parameters

##### message

[`ILockChatAction`](../interfaces/ILockChatAction.md)

LockChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:46337](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46337)

Creates a LockChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LockChatAction`](LockChatAction.md)

LockChatAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:46358](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46358)

Gets the default type url for LockChatAction

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

Defined in: [WAProto/index.d.ts:46345](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46345)

Creates a plain object from a LockChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`LockChatAction`](LockChatAction.md)

LockChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:46330](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L46330)

Verifies a LockChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
