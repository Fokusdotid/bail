# Class: BizAccountLinkInfo

Defined in: [WAProto/index.d.ts:3245](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3245)

Represents a BizAccountLinkInfo.

## Implements

- [`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

## Constructors

### new BizAccountLinkInfo()

> **new BizAccountLinkInfo**(`properties`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:3251](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3251)

Constructs a new BizAccountLinkInfo.

#### Parameters

##### properties?

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

Properties to set

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

## Properties

### accountType?

> `optional` **accountType**: `null` \| [`ENTERPRISE`](../namespaces/BizAccountLinkInfo/enumerations/AccountType.md#enterprise)

Defined in: [WAProto/index.d.ts:3266](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3266)

BizAccountLinkInfo accountType.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`accountType`](../interfaces/IBizAccountLinkInfo.md#accounttype)

***

### hostStorage?

> `optional` **hostStorage**: `null` \| [`HostStorageType`](../namespaces/BizAccountLinkInfo/enumerations/HostStorageType.md)

Defined in: [WAProto/index.d.ts:3263](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3263)

BizAccountLinkInfo hostStorage.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`hostStorage`](../interfaces/IBizAccountLinkInfo.md#hoststorage)

***

### issueTime?

> `optional` **issueTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3260](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3260)

BizAccountLinkInfo issueTime.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`issueTime`](../interfaces/IBizAccountLinkInfo.md#issuetime)

***

### whatsappAcctNumber?

> `optional` **whatsappAcctNumber**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3257](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3257)

BizAccountLinkInfo whatsappAcctNumber.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`whatsappAcctNumber`](../interfaces/IBizAccountLinkInfo.md#whatsappacctnumber)

***

### whatsappBizAcctFbid?

> `optional` **whatsappBizAcctFbid**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3254](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3254)

BizAccountLinkInfo whatsappBizAcctFbid.

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`whatsappBizAcctFbid`](../interfaces/IBizAccountLinkInfo.md#whatsappbizacctfbid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3336](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3336)

Converts this BizAccountLinkInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:3273](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3273)

Creates a new BizAccountLinkInfo instance using the specified properties.

#### Parameters

##### properties?

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

Properties to set

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:3299](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3299)

Decodes a BizAccountLinkInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:3308](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3308)

Decodes a BizAccountLinkInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3281](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3281)

Encodes the specified BizAccountLinkInfo message. Does not implicitly [verify](BizAccountLinkInfo.md#verify) messages.

#### Parameters

##### message

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

BizAccountLinkInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3289](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3289)

Encodes the specified BizAccountLinkInfo message, length delimited. Does not implicitly [verify](BizAccountLinkInfo.md#verify) messages.

#### Parameters

##### message

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

BizAccountLinkInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:3322](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3322)

Creates a BizAccountLinkInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3343](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3343)

Gets the default type url for BizAccountLinkInfo

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

Defined in: [WAProto/index.d.ts:3330](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3330)

Creates a plain object from a BizAccountLinkInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

BizAccountLinkInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3315](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L3315)

Verifies a BizAccountLinkInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
