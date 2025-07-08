# Class: SyncdPatch

Defined in: [WAProto/index.d.ts:50195](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50195)

Represents a SyncdPatch.

## Implements

- [`ISyncdPatch`](../interfaces/ISyncdPatch.md)

## Constructors

### new SyncdPatch()

> **new SyncdPatch**(`properties`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:50201](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50201)

Constructs a new SyncdPatch.

#### Parameters

##### properties?

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

Properties to set

#### Returns

[`SyncdPatch`](SyncdPatch.md)

## Properties

### clientDebugData?

> `optional` **clientDebugData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:50228](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50228)

SyncdPatch clientDebugData.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`clientDebugData`](../interfaces/ISyncdPatch.md#clientdebugdata)

***

### deviceIndex?

> `optional` **deviceIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:50225](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50225)

SyncdPatch deviceIndex.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`deviceIndex`](../interfaces/ISyncdPatch.md#deviceindex)

***

### exitCode?

> `optional` **exitCode**: `null` \| [`IExitCode`](../interfaces/IExitCode.md)

Defined in: [WAProto/index.d.ts:50222](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50222)

SyncdPatch exitCode.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`exitCode`](../interfaces/ISyncdPatch.md#exitcode)

***

### externalMutations?

> `optional` **externalMutations**: `null` \| [`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:50210](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50210)

SyncdPatch externalMutations.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`externalMutations`](../interfaces/ISyncdPatch.md#externalmutations)

***

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:50219](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50219)

SyncdPatch keyId.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`keyId`](../interfaces/ISyncdPatch.md#keyid)

***

### mutations

> **mutations**: [`ISyncdMutation`](../interfaces/ISyncdMutation.md)[]

Defined in: [WAProto/index.d.ts:50207](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50207)

SyncdPatch mutations.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`mutations`](../interfaces/ISyncdPatch.md#mutations)

***

### patchMac?

> `optional` **patchMac**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:50216](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50216)

SyncdPatch patchMac.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`patchMac`](../interfaces/ISyncdPatch.md#patchmac)

***

### snapshotMac?

> `optional` **snapshotMac**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:50213](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50213)

SyncdPatch snapshotMac.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`snapshotMac`](../interfaces/ISyncdPatch.md#snapshotmac)

***

### version?

> `optional` **version**: `null` \| [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Defined in: [WAProto/index.d.ts:50204](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50204)

SyncdPatch version.

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`version`](../interfaces/ISyncdPatch.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50298](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50298)

Converts this SyncdPatch to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:50235](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50235)

Creates a new SyncdPatch instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

Properties to set

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:50261](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50261)

Decodes a SyncdPatch message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:50270](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50270)

Decodes a SyncdPatch message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50243](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50243)

Encodes the specified SyncdPatch message. Does not implicitly [verify](SyncdPatch.md#verify) messages.

#### Parameters

##### message

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

SyncdPatch message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50251](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50251)

Encodes the specified SyncdPatch message, length delimited. Does not implicitly [verify](SyncdPatch.md#verify) messages.

#### Parameters

##### message

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

SyncdPatch message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:50284](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50284)

Creates a SyncdPatch message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50305](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50305)

Gets the default type url for SyncdPatch

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

Defined in: [WAProto/index.d.ts:50292](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50292)

Creates a plain object from a SyncdPatch message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdPatch`](SyncdPatch.md)

SyncdPatch

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50277](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50277)

Verifies a SyncdPatch message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
