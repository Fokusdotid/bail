# Class: PendingPreKey

Defined in: [WAProto/index.d.ts:42432](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42432)

Represents a PendingPreKey.

## Implements

- [`IPendingPreKey`](../interfaces/IPendingPreKey.md)

## Constructors

### new PendingPreKey()

> **new PendingPreKey**(`properties`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:42438](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42438)

Constructs a new PendingPreKey.

#### Parameters

##### properties?

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

Properties to set

#### Returns

[`PendingPreKey`](PendingPreKey.md)

## Properties

### baseKey?

> `optional` **baseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42447](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42447)

PendingPreKey baseKey.

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`baseKey`](../interfaces/IPendingPreKey.md#basekey)

***

### preKeyId?

> `optional` **preKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:42441](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42441)

PendingPreKey preKeyId.

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`preKeyId`](../interfaces/IPendingPreKey.md#prekeyid)

***

### signedPreKeyId?

> `optional` **signedPreKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:42444](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42444)

PendingPreKey signedPreKeyId.

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`signedPreKeyId`](../interfaces/IPendingPreKey.md#signedprekeyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:42517](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42517)

Converts this PendingPreKey to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:42454](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42454)

Creates a new PendingPreKey instance using the specified properties.

#### Parameters

##### properties?

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

Properties to set

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:42480](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42480)

Decodes a PendingPreKey message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:42489](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42489)

Decodes a PendingPreKey message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42462](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42462)

Encodes the specified PendingPreKey message. Does not implicitly [verify](PendingPreKey.md#verify) messages.

#### Parameters

##### message

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

PendingPreKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42470](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42470)

Encodes the specified PendingPreKey message, length delimited. Does not implicitly [verify](PendingPreKey.md#verify) messages.

#### Parameters

##### message

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

PendingPreKey message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:42503](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42503)

Creates a PendingPreKey message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:42524](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42524)

Gets the default type url for PendingPreKey

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

Defined in: [WAProto/index.d.ts:42511](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42511)

Creates a plain object from a PendingPreKey message. Also converts values to other types if specified.

#### Parameters

##### message

[`PendingPreKey`](PendingPreKey.md)

PendingPreKey

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:42496](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L42496)

Verifies a PendingPreKey message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
