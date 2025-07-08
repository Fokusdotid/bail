# Class: IdentityKeyPairStructure

Defined in: [WAProto/index.d.ts:16541](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16541)

Represents an IdentityKeyPairStructure.

## Implements

- [`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

## Constructors

### new IdentityKeyPairStructure()

> **new IdentityKeyPairStructure**(`properties`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:16547](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16547)

Constructs a new IdentityKeyPairStructure.

#### Parameters

##### properties?

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

Properties to set

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

## Properties

### privateKey?

> `optional` **privateKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:16553](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16553)

IdentityKeyPairStructure privateKey.

#### Implementation of

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md).[`privateKey`](../interfaces/IIdentityKeyPairStructure.md#privatekey)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:16550](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16550)

IdentityKeyPairStructure publicKey.

#### Implementation of

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md).[`publicKey`](../interfaces/IIdentityKeyPairStructure.md#publickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16623](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16623)

Converts this IdentityKeyPairStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:16560](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16560)

Creates a new IdentityKeyPairStructure instance using the specified properties.

#### Parameters

##### properties?

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

Properties to set

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:16586](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16586)

Decodes an IdentityKeyPairStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:16595](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16595)

Decodes an IdentityKeyPairStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16568](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16568)

Encodes the specified IdentityKeyPairStructure message. Does not implicitly [verify](IdentityKeyPairStructure.md#verify) messages.

#### Parameters

##### message

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

IdentityKeyPairStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16576](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16576)

Encodes the specified IdentityKeyPairStructure message, length delimited. Does not implicitly [verify](IdentityKeyPairStructure.md#verify) messages.

#### Parameters

##### message

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

IdentityKeyPairStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:16609](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16609)

Creates an IdentityKeyPairStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:16630](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16630)

Gets the default type url for IdentityKeyPairStructure

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

Defined in: [WAProto/index.d.ts:16617](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16617)

Creates a plain object from an IdentityKeyPairStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

IdentityKeyPairStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16602](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16602)

Verifies an IdentityKeyPairStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
