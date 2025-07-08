# Class: SyncDCollectionFatalRecoveryRequest

Defined in: [WAProto/index.d.ts:29918](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29918)

Represents a SyncDCollectionFatalRecoveryRequest.

## Implements

- [`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

## Constructors

### new SyncDCollectionFatalRecoveryRequest()

> **new SyncDCollectionFatalRecoveryRequest**(`properties`?): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:29924](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29924)

Constructs a new SyncDCollectionFatalRecoveryRequest.

#### Parameters

##### properties?

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

Properties to set

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

## Properties

### collectionName?

> `optional` **collectionName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:29927](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29927)

SyncDCollectionFatalRecoveryRequest collectionName.

#### Implementation of

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md).[`collectionName`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md#collectionname)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:29930](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29930)

SyncDCollectionFatalRecoveryRequest timestamp.

#### Implementation of

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md).[`timestamp`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30000](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30000)

Converts this SyncDCollectionFatalRecoveryRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:29937](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29937)

Creates a new SyncDCollectionFatalRecoveryRequest instance using the specified properties.

#### Parameters

##### properties?

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

Properties to set

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

SyncDCollectionFatalRecoveryRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:29963](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29963)

Decodes a SyncDCollectionFatalRecoveryRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

SyncDCollectionFatalRecoveryRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:29972](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29972)

Decodes a SyncDCollectionFatalRecoveryRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

SyncDCollectionFatalRecoveryRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29945](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29945)

Encodes the specified SyncDCollectionFatalRecoveryRequest message. Does not implicitly [verify](SyncDCollectionFatalRecoveryRequest.md#verify) messages.

#### Parameters

##### message

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

SyncDCollectionFatalRecoveryRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29953](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29953)

Encodes the specified SyncDCollectionFatalRecoveryRequest message, length delimited. Does not implicitly [verify](SyncDCollectionFatalRecoveryRequest.md#verify) messages.

#### Parameters

##### message

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

SyncDCollectionFatalRecoveryRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:29986](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29986)

Creates a SyncDCollectionFatalRecoveryRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

SyncDCollectionFatalRecoveryRequest

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:30007](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L30007)

Gets the default type url for SyncDCollectionFatalRecoveryRequest

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

Defined in: [WAProto/index.d.ts:29994](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29994)

Creates a plain object from a SyncDCollectionFatalRecoveryRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

SyncDCollectionFatalRecoveryRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29979](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L29979)

Verifies a SyncDCollectionFatalRecoveryRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
