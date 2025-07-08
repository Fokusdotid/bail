# Class: SyncDSnapshotFatalRecoveryResponse

Defined in: [WAProto/index.d.ts:30851](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30851)

Represents a SyncDSnapshotFatalRecoveryResponse.

## Implements

- [`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

## Constructors

### new SyncDSnapshotFatalRecoveryResponse()

> **new SyncDSnapshotFatalRecoveryResponse**(`properties`?): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:30857](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30857)

Constructs a new SyncDSnapshotFatalRecoveryResponse.

#### Parameters

##### properties?

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

Properties to set

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

## Properties

### collectionSnapshot?

> `optional` **collectionSnapshot**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:30860](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30860)

SyncDSnapshotFatalRecoveryResponse collectionSnapshot.

#### Implementation of

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md).[`collectionSnapshot`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md#collectionsnapshot)

***

### isCompressed?

> `optional` **isCompressed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:30863](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30863)

SyncDSnapshotFatalRecoveryResponse isCompressed.

#### Implementation of

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md).[`isCompressed`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md#iscompressed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30933](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30933)

Converts this SyncDSnapshotFatalRecoveryResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:30870](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30870)

Creates a new SyncDSnapshotFatalRecoveryResponse instance using the specified properties.

#### Parameters

##### properties?

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

Properties to set

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

SyncDSnapshotFatalRecoveryResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:30896](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30896)

Decodes a SyncDSnapshotFatalRecoveryResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

SyncDSnapshotFatalRecoveryResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:30905](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30905)

Decodes a SyncDSnapshotFatalRecoveryResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

SyncDSnapshotFatalRecoveryResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30878](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30878)

Encodes the specified SyncDSnapshotFatalRecoveryResponse message. Does not implicitly [verify](SyncDSnapshotFatalRecoveryResponse.md#verify) messages.

#### Parameters

##### message

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

SyncDSnapshotFatalRecoveryResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30886](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30886)

Encodes the specified SyncDSnapshotFatalRecoveryResponse message, length delimited. Does not implicitly [verify](SyncDSnapshotFatalRecoveryResponse.md#verify) messages.

#### Parameters

##### message

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

SyncDSnapshotFatalRecoveryResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:30919](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30919)

Creates a SyncDSnapshotFatalRecoveryResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

SyncDSnapshotFatalRecoveryResponse

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:30940](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30940)

Gets the default type url for SyncDSnapshotFatalRecoveryResponse

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

Defined in: [WAProto/index.d.ts:30927](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30927)

Creates a plain object from a SyncDSnapshotFatalRecoveryResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

SyncDSnapshotFatalRecoveryResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30912](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L30912)

Verifies a SyncDSnapshotFatalRecoveryResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
