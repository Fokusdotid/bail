# Class: UserReceipt

Defined in: [WAProto/index.d.ts:51840](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51840)

Represents a UserReceipt.

## Implements

- [`IUserReceipt`](../interfaces/IUserReceipt.md)

## Constructors

### new UserReceipt()

> **new UserReceipt**(`properties`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:51846](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51846)

Constructs a new UserReceipt.

#### Parameters

##### properties?

[`IUserReceipt`](../interfaces/IUserReceipt.md)

Properties to set

#### Returns

[`UserReceipt`](UserReceipt.md)

## Properties

### deliveredDeviceJid

> **deliveredDeviceJid**: `string`[]

Defined in: [WAProto/index.d.ts:51864](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51864)

UserReceipt deliveredDeviceJid.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`deliveredDeviceJid`](../interfaces/IUserReceipt.md#delivereddevicejid)

***

### pendingDeviceJid

> **pendingDeviceJid**: `string`[]

Defined in: [WAProto/index.d.ts:51861](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51861)

UserReceipt pendingDeviceJid.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`pendingDeviceJid`](../interfaces/IUserReceipt.md#pendingdevicejid)

***

### playedTimestamp?

> `optional` **playedTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:51858](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51858)

UserReceipt playedTimestamp.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`playedTimestamp`](../interfaces/IUserReceipt.md#playedtimestamp)

***

### readTimestamp?

> `optional` **readTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:51855](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51855)

UserReceipt readTimestamp.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`readTimestamp`](../interfaces/IUserReceipt.md#readtimestamp)

***

### receiptTimestamp?

> `optional` **receiptTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:51852](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51852)

UserReceipt receiptTimestamp.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`receiptTimestamp`](../interfaces/IUserReceipt.md#receipttimestamp)

***

### userJid

> **userJid**: `string`

Defined in: [WAProto/index.d.ts:51849](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51849)

UserReceipt userJid.

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`userJid`](../interfaces/IUserReceipt.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51934](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51934)

Converts this UserReceipt to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:51871](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51871)

Creates a new UserReceipt instance using the specified properties.

#### Parameters

##### properties?

[`IUserReceipt`](../interfaces/IUserReceipt.md)

Properties to set

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:51897](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51897)

Decodes a UserReceipt message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:51906](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51906)

Decodes a UserReceipt message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51879](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51879)

Encodes the specified UserReceipt message. Does not implicitly [verify](UserReceipt.md#verify) messages.

#### Parameters

##### message

[`IUserReceipt`](../interfaces/IUserReceipt.md)

UserReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51887](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51887)

Encodes the specified UserReceipt message, length delimited. Does not implicitly [verify](UserReceipt.md#verify) messages.

#### Parameters

##### message

[`IUserReceipt`](../interfaces/IUserReceipt.md)

UserReceipt message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:51920](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51920)

Creates a UserReceipt message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UserReceipt`](UserReceipt.md)

UserReceipt

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51941](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51941)

Gets the default type url for UserReceipt

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

Defined in: [WAProto/index.d.ts:51928](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51928)

Creates a plain object from a UserReceipt message. Also converts values to other types if specified.

#### Parameters

##### message

[`UserReceipt`](UserReceipt.md)

UserReceipt

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51913](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51913)

Verifies a UserReceipt message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
