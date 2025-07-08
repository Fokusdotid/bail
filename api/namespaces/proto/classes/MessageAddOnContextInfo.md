# Class: MessageAddOnContextInfo

Defined in: [WAProto/index.d.ts:35725](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35725)

Represents a MessageAddOnContextInfo.

## Implements

- [`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

## Constructors

### new MessageAddOnContextInfo()

> **new MessageAddOnContextInfo**(`properties`?): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:35731](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35731)

Constructs a new MessageAddOnContextInfo.

#### Parameters

##### properties?

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Properties to set

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

## Properties

### messageAddOnDurationInSecs?

> `optional` **messageAddOnDurationInSecs**: `null` \| `number`

Defined in: [WAProto/index.d.ts:35734](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35734)

MessageAddOnContextInfo messageAddOnDurationInSecs.

#### Implementation of

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md).[`messageAddOnDurationInSecs`](../interfaces/IMessageAddOnContextInfo.md#messageaddondurationinsecs)

***

### messageAddOnExpiryType?

> `optional` **messageAddOnExpiryType**: `null` \| [`MessageAddonExpiryType`](../namespaces/MessageContextInfo/enumerations/MessageAddonExpiryType.md)

Defined in: [WAProto/index.d.ts:35737](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35737)

MessageAddOnContextInfo messageAddOnExpiryType.

#### Implementation of

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md).[`messageAddOnExpiryType`](../interfaces/IMessageAddOnContextInfo.md#messageaddonexpirytype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35807](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35807)

Converts this MessageAddOnContextInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:35744](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35744)

Creates a new MessageAddOnContextInfo instance using the specified properties.

#### Parameters

##### properties?

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Properties to set

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:35770](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35770)

Decodes a MessageAddOnContextInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:35779](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35779)

Decodes a MessageAddOnContextInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35752](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35752)

Encodes the specified MessageAddOnContextInfo message. Does not implicitly [verify](MessageAddOnContextInfo.md#verify) messages.

#### Parameters

##### message

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

MessageAddOnContextInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35760](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35760)

Encodes the specified MessageAddOnContextInfo message, length delimited. Does not implicitly [verify](MessageAddOnContextInfo.md#verify) messages.

#### Parameters

##### message

[`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

MessageAddOnContextInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:35793](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35793)

Creates a MessageAddOnContextInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:35814](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35814)

Gets the default type url for MessageAddOnContextInfo

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

Defined in: [WAProto/index.d.ts:35801](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35801)

Creates a plain object from a MessageAddOnContextInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`MessageAddOnContextInfo`](MessageAddOnContextInfo.md)

MessageAddOnContextInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35786](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L35786)

Verifies a MessageAddOnContextInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
