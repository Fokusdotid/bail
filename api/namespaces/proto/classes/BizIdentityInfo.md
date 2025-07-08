# Class: BizIdentityInfo

Defined in: [WAProto/index.d.ts:3492](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3492)

Represents a BizIdentityInfo.

## Implements

- [`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

## Constructors

### new BizIdentityInfo()

> **new BizIdentityInfo**(`properties`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:3498](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3498)

Constructs a new BizIdentityInfo.

#### Parameters

##### properties?

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

Properties to set

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

## Properties

### actualActors?

> `optional` **actualActors**: `null` \| [`ActualActorsType`](../namespaces/BizIdentityInfo/enumerations/ActualActorsType.md)

Defined in: [WAProto/index.d.ts:3516](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3516)

BizIdentityInfo actualActors.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`actualActors`](../interfaces/IBizIdentityInfo.md#actualactors)

***

### featureControls?

> `optional` **featureControls**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3522](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3522)

BizIdentityInfo featureControls.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`featureControls`](../interfaces/IBizIdentityInfo.md#featurecontrols)

***

### hostStorage?

> `optional` **hostStorage**: `null` \| [`HostStorageType`](../namespaces/BizIdentityInfo/enumerations/HostStorageType.md)

Defined in: [WAProto/index.d.ts:3513](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3513)

BizIdentityInfo hostStorage.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`hostStorage`](../interfaces/IBizIdentityInfo.md#hoststorage)

***

### privacyModeTs?

> `optional` **privacyModeTs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3519](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3519)

BizIdentityInfo privacyModeTs.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`privacyModeTs`](../interfaces/IBizIdentityInfo.md#privacymodets)

***

### revoked?

> `optional` **revoked**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3510](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3510)

BizIdentityInfo revoked.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`revoked`](../interfaces/IBizIdentityInfo.md#revoked)

***

### signed?

> `optional` **signed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3507](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3507)

BizIdentityInfo signed.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`signed`](../interfaces/IBizIdentityInfo.md#signed)

***

### vlevel?

> `optional` **vlevel**: `null` \| [`VerifiedLevelValue`](../namespaces/BizIdentityInfo/enumerations/VerifiedLevelValue.md)

Defined in: [WAProto/index.d.ts:3501](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3501)

BizIdentityInfo vlevel.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`vlevel`](../interfaces/IBizIdentityInfo.md#vlevel)

***

### vnameCert?

> `optional` **vnameCert**: `null` \| [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:3504](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3504)

BizIdentityInfo vnameCert.

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`vnameCert`](../interfaces/IBizIdentityInfo.md#vnamecert)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3592](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3592)

Converts this BizIdentityInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:3529](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3529)

Creates a new BizIdentityInfo instance using the specified properties.

#### Parameters

##### properties?

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

Properties to set

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:3555](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3555)

Decodes a BizIdentityInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:3564](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3564)

Decodes a BizIdentityInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3537](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3537)

Encodes the specified BizIdentityInfo message. Does not implicitly [verify](BizIdentityInfo.md#verify) messages.

#### Parameters

##### message

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

BizIdentityInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3545](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3545)

Encodes the specified BizIdentityInfo message, length delimited. Does not implicitly [verify](BizIdentityInfo.md#verify) messages.

#### Parameters

##### message

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

BizIdentityInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:3578](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3578)

Creates a BizIdentityInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3599](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3599)

Gets the default type url for BizIdentityInfo

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

Defined in: [WAProto/index.d.ts:3586](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3586)

Creates a plain object from a BizIdentityInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`BizIdentityInfo`](BizIdentityInfo.md)

BizIdentityInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3571](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L3571)

Verifies a BizIdentityInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
