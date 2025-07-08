# Class: DeviceListMetadata

Defined in: [WAProto/index.d.ts:13072](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13072)

Represents a DeviceListMetadata.

## Implements

- [`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

## Constructors

### new DeviceListMetadata()

> **new DeviceListMetadata**(`properties`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:13078](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13078)

Constructs a new DeviceListMetadata.

#### Parameters

##### properties?

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

Properties to set

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

## Properties

### receiverAccountType?

> `optional` **receiverAccountType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:13093](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13093)

DeviceListMetadata receiverAccountType.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`receiverAccountType`](../interfaces/IDeviceListMetadata.md#receiveraccounttype)

***

### recipientKeyHash?

> `optional` **recipientKeyHash**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13096](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13096)

DeviceListMetadata recipientKeyHash.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientKeyHash`](../interfaces/IDeviceListMetadata.md#recipientkeyhash)

***

### recipientKeyIndexes

> **recipientKeyIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:13102](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13102)

DeviceListMetadata recipientKeyIndexes.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientKeyIndexes`](../interfaces/IDeviceListMetadata.md#recipientkeyindexes)

***

### recipientTimestamp?

> `optional` **recipientTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13099](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13099)

DeviceListMetadata recipientTimestamp.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientTimestamp`](../interfaces/IDeviceListMetadata.md#recipienttimestamp)

***

### senderAccountType?

> `optional` **senderAccountType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:13090](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13090)

DeviceListMetadata senderAccountType.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderAccountType`](../interfaces/IDeviceListMetadata.md#senderaccounttype)

***

### senderKeyHash?

> `optional` **senderKeyHash**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13081](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13081)

DeviceListMetadata senderKeyHash.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderKeyHash`](../interfaces/IDeviceListMetadata.md#senderkeyhash)

***

### senderKeyIndexes

> **senderKeyIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:13087](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13087)

DeviceListMetadata senderKeyIndexes.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderKeyIndexes`](../interfaces/IDeviceListMetadata.md#senderkeyindexes)

***

### senderTimestamp?

> `optional` **senderTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13084](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13084)

DeviceListMetadata senderTimestamp.

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderTimestamp`](../interfaces/IDeviceListMetadata.md#sendertimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13172](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13172)

Converts this DeviceListMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:13109](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13109)

Creates a new DeviceListMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

Properties to set

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:13135](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13135)

Decodes a DeviceListMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:13144](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13144)

Decodes a DeviceListMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13117](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13117)

Encodes the specified DeviceListMetadata message. Does not implicitly [verify](DeviceListMetadata.md#verify) messages.

#### Parameters

##### message

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

DeviceListMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13125](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13125)

Encodes the specified DeviceListMetadata message, length delimited. Does not implicitly [verify](DeviceListMetadata.md#verify) messages.

#### Parameters

##### message

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

DeviceListMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:13158](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13158)

Creates a DeviceListMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13179](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13179)

Gets the default type url for DeviceListMetadata

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

Defined in: [WAProto/index.d.ts:13166](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13166)

Creates a plain object from a DeviceListMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeviceListMetadata`](DeviceListMetadata.md)

DeviceListMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13151](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L13151)

Verifies a DeviceListMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
