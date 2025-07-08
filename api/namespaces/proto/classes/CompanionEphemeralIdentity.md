# Class: CompanionEphemeralIdentity

Defined in: [WAProto/index.d.ts:10539](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10539)

Represents a CompanionEphemeralIdentity.

## Implements

- [`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

## Constructors

### new CompanionEphemeralIdentity()

> **new CompanionEphemeralIdentity**(`properties`?): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10545](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10545)

Constructs a new CompanionEphemeralIdentity.

#### Parameters

##### properties?

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

Properties to set

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

## Properties

### deviceType?

> `optional` **deviceType**: `null` \| [`PlatformType`](../namespaces/DeviceProps/enumerations/PlatformType.md)

Defined in: [WAProto/index.d.ts:10551](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10551)

CompanionEphemeralIdentity deviceType.

#### Implementation of

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md).[`deviceType`](../interfaces/ICompanionEphemeralIdentity.md#devicetype)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10548](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10548)

CompanionEphemeralIdentity publicKey.

#### Implementation of

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md).[`publicKey`](../interfaces/ICompanionEphemeralIdentity.md#publickey)

***

### ref?

> `optional` **ref**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10554](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10554)

CompanionEphemeralIdentity ref.

#### Implementation of

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md).[`ref`](../interfaces/ICompanionEphemeralIdentity.md#ref)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10624](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10624)

Converts this CompanionEphemeralIdentity to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10561](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10561)

Creates a new CompanionEphemeralIdentity instance using the specified properties.

#### Parameters

##### properties?

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

Properties to set

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

CompanionEphemeralIdentity instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10587](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10587)

Decodes a CompanionEphemeralIdentity message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

CompanionEphemeralIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10596](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10596)

Decodes a CompanionEphemeralIdentity message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

CompanionEphemeralIdentity

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10569](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10569)

Encodes the specified CompanionEphemeralIdentity message. Does not implicitly [verify](CompanionEphemeralIdentity.md#verify) messages.

#### Parameters

##### message

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

CompanionEphemeralIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:10577](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10577)

Encodes the specified CompanionEphemeralIdentity message, length delimited. Does not implicitly [verify](CompanionEphemeralIdentity.md#verify) messages.

#### Parameters

##### message

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

CompanionEphemeralIdentity message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10610](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10610)

Creates a CompanionEphemeralIdentity message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

CompanionEphemeralIdentity

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10631](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10631)

Gets the default type url for CompanionEphemeralIdentity

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

Defined in: [WAProto/index.d.ts:10618](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10618)

Creates a plain object from a CompanionEphemeralIdentity message. Also converts values to other types if specified.

#### Parameters

##### message

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

CompanionEphemeralIdentity

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:10603](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L10603)

Verifies a CompanionEphemeralIdentity message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
