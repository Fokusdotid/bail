# Class: ClientPairingProps

Defined in: [WAProto/index.d.ts:8884](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8884)

Represents a ClientPairingProps.

## Implements

- [`IClientPairingProps`](../interfaces/IClientPairingProps.md)

## Constructors

### new ClientPairingProps()

> **new ClientPairingProps**(`properties`?): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:8890](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8890)

Constructs a new ClientPairingProps.

#### Parameters

##### properties?

[`IClientPairingProps`](../interfaces/IClientPairingProps.md)

Properties to set

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

## Properties

### isChatDbLidMigrated?

> `optional` **isChatDbLidMigrated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:8893](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8893)

ClientPairingProps isChatDbLidMigrated.

#### Implementation of

[`IClientPairingProps`](../interfaces/IClientPairingProps.md).[`isChatDbLidMigrated`](../interfaces/IClientPairingProps.md#ischatdblidmigrated)

***

### isSyncdPureLidSession?

> `optional` **isSyncdPureLidSession**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:8896](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8896)

ClientPairingProps isSyncdPureLidSession.

#### Implementation of

[`IClientPairingProps`](../interfaces/IClientPairingProps.md).[`isSyncdPureLidSession`](../interfaces/IClientPairingProps.md#issyncdpurelidsession)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8966](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8966)

Converts this ClientPairingProps to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:8903](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8903)

Creates a new ClientPairingProps instance using the specified properties.

#### Parameters

##### properties?

[`IClientPairingProps`](../interfaces/IClientPairingProps.md)

Properties to set

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

ClientPairingProps instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:8929](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8929)

Decodes a ClientPairingProps message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

ClientPairingProps

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:8938](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8938)

Decodes a ClientPairingProps message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

ClientPairingProps

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8911](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8911)

Encodes the specified ClientPairingProps message. Does not implicitly [verify](ClientPairingProps.md#verify) messages.

#### Parameters

##### message

[`IClientPairingProps`](../interfaces/IClientPairingProps.md)

ClientPairingProps message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:8919](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8919)

Encodes the specified ClientPairingProps message, length delimited. Does not implicitly [verify](ClientPairingProps.md#verify) messages.

#### Parameters

##### message

[`IClientPairingProps`](../interfaces/IClientPairingProps.md)

ClientPairingProps message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:8952](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8952)

Creates a ClientPairingProps message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

ClientPairingProps

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8973](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8973)

Gets the default type url for ClientPairingProps

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

Defined in: [WAProto/index.d.ts:8960](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8960)

Creates a plain object from a ClientPairingProps message. Also converts values to other types if specified.

#### Parameters

##### message

[`ClientPairingProps`](ClientPairingProps.md)

ClientPairingProps

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:8945](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L8945)

Verifies a ClientPairingProps message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
