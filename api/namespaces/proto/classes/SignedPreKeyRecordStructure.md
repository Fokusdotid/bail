# Class: SignedPreKeyRecordStructure

Defined in: [WAProto/index.d.ts:42663](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42663)

Represents a SignedPreKeyRecordStructure.

## Implements

- [`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

## Constructors

### new SignedPreKeyRecordStructure()

> **new SignedPreKeyRecordStructure**(`properties`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:42669](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42669)

Constructs a new SignedPreKeyRecordStructure.

#### Parameters

##### properties?

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

Properties to set

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

## Properties

### id?

> `optional` **id**: `null` \| `number`

Defined in: [WAProto/index.d.ts:42672](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42672)

SignedPreKeyRecordStructure id.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`id`](../interfaces/ISignedPreKeyRecordStructure.md#id)

***

### privateKey?

> `optional` **privateKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42678](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42678)

SignedPreKeyRecordStructure privateKey.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`privateKey`](../interfaces/ISignedPreKeyRecordStructure.md#privatekey)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42675](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42675)

SignedPreKeyRecordStructure publicKey.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`publicKey`](../interfaces/ISignedPreKeyRecordStructure.md#publickey)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:42681](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42681)

SignedPreKeyRecordStructure signature.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`signature`](../interfaces/ISignedPreKeyRecordStructure.md#signature)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:42684](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42684)

SignedPreKeyRecordStructure timestamp.

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`timestamp`](../interfaces/ISignedPreKeyRecordStructure.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:42754](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42754)

Converts this SignedPreKeyRecordStructure to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:42691](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42691)

Creates a new SignedPreKeyRecordStructure instance using the specified properties.

#### Parameters

##### properties?

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

Properties to set

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:42717](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42717)

Decodes a SignedPreKeyRecordStructure message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:42726](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42726)

Decodes a SignedPreKeyRecordStructure message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42699](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42699)

Encodes the specified SignedPreKeyRecordStructure message. Does not implicitly [verify](SignedPreKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42707](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42707)

Encodes the specified SignedPreKeyRecordStructure message, length delimited. Does not implicitly [verify](SignedPreKeyRecordStructure.md#verify) messages.

#### Parameters

##### message

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:42740](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42740)

Creates a SignedPreKeyRecordStructure message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:42761](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42761)

Gets the default type url for SignedPreKeyRecordStructure

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

Defined in: [WAProto/index.d.ts:42748](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42748)

Creates a plain object from a SignedPreKeyRecordStructure message. Also converts values to other types if specified.

#### Parameters

##### message

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

SignedPreKeyRecordStructure

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:42733](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L42733)

Verifies a SignedPreKeyRecordStructure message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
