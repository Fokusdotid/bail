# Class: NativeFlowInfo

Defined in: [WAProto/index.d.ts:20631](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20631)

Represents a NativeFlowInfo.

## Implements

- [`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

## Constructors

### new NativeFlowInfo()

> **new NativeFlowInfo**(`properties`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:20637](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20637)

Constructs a new NativeFlowInfo.

#### Parameters

##### properties?

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

Properties to set

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

## Properties

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20640](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20640)

NativeFlowInfo name.

#### Implementation of

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md).[`name`](../interfaces/INativeFlowInfo.md#name)

***

### paramsJson?

> `optional` **paramsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20643](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20643)

NativeFlowInfo paramsJson.

#### Implementation of

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md).[`paramsJson`](../interfaces/INativeFlowInfo.md#paramsjson)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20713](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20713)

Converts this NativeFlowInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:20650](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20650)

Creates a new NativeFlowInfo instance using the specified properties.

#### Parameters

##### properties?

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

Properties to set

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:20676](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20676)

Decodes a NativeFlowInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:20685](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20685)

Decodes a NativeFlowInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20658](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20658)

Encodes the specified NativeFlowInfo message. Does not implicitly [verify](NativeFlowInfo.md#verify) messages.

#### Parameters

##### message

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

NativeFlowInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20666](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20666)

Encodes the specified NativeFlowInfo message, length delimited. Does not implicitly [verify](NativeFlowInfo.md#verify) messages.

#### Parameters

##### message

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

NativeFlowInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:20699](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20699)

Creates a NativeFlowInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:20720](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20720)

Gets the default type url for NativeFlowInfo

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

Defined in: [WAProto/index.d.ts:20707](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20707)

Creates a plain object from a NativeFlowInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`NativeFlowInfo`](NativeFlowInfo.md)

NativeFlowInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20692](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L20692)

Verifies a NativeFlowInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
