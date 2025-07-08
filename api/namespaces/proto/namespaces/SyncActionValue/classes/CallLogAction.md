# Class: CallLogAction

Defined in: [WAProto/index.d.ts:44091](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44091)

Represents a CallLogAction.

## Implements

- [`ICallLogAction`](../interfaces/ICallLogAction.md)

## Constructors

### new CallLogAction()

> **new CallLogAction**(`properties`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:44097](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44097)

Constructs a new CallLogAction.

#### Parameters

##### properties?

[`ICallLogAction`](../interfaces/ICallLogAction.md)

Properties to set

#### Returns

[`CallLogAction`](CallLogAction.md)

## Properties

### callLogRecord?

> `optional` **callLogRecord**: `null` \| [`ICallLogRecord`](../../../interfaces/ICallLogRecord.md)

Defined in: [WAProto/index.d.ts:44100](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44100)

CallLogAction callLogRecord.

#### Implementation of

[`ICallLogAction`](../interfaces/ICallLogAction.md).[`callLogRecord`](../interfaces/ICallLogAction.md#calllogrecord)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:44170](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44170)

Converts this CallLogAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:44107](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44107)

Creates a new CallLogAction instance using the specified properties.

#### Parameters

##### properties?

[`ICallLogAction`](../interfaces/ICallLogAction.md)

Properties to set

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:44133](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44133)

Decodes a CallLogAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:44142](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44142)

Decodes a CallLogAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44115](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44115)

Encodes the specified CallLogAction message. Does not implicitly [verify](CallLogAction.md#verify) messages.

#### Parameters

##### message

[`ICallLogAction`](../interfaces/ICallLogAction.md)

CallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44123](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44123)

Encodes the specified CallLogAction message, length delimited. Does not implicitly [verify](CallLogAction.md#verify) messages.

#### Parameters

##### message

[`ICallLogAction`](../interfaces/ICallLogAction.md)

CallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:44156](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44156)

Creates a CallLogAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CallLogAction`](CallLogAction.md)

CallLogAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:44177](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44177)

Gets the default type url for CallLogAction

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

Defined in: [WAProto/index.d.ts:44164](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44164)

Creates a plain object from a CallLogAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`CallLogAction`](CallLogAction.md)

CallLogAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44149](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L44149)

Verifies a CallLogAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
