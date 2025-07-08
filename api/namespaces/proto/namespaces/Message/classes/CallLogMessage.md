# Class: CallLogMessage

Defined in: [WAProto/index.d.ts:21023](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21023)

Represents a CallLogMessage.

## Implements

- [`ICallLogMessage`](../interfaces/ICallLogMessage.md)

## Constructors

### new CallLogMessage()

> **new CallLogMessage**(`properties`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:21029](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21029)

Constructs a new CallLogMessage.

#### Parameters

##### properties?

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

Properties to set

#### Returns

[`CallLogMessage`](CallLogMessage.md)

## Properties

### callOutcome?

> `optional` **callOutcome**: `null` \| [`CallOutcome`](../namespaces/CallLogMessage/enumerations/CallOutcome.md)

Defined in: [WAProto/index.d.ts:21035](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21035)

CallLogMessage callOutcome.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`callOutcome`](../interfaces/ICallLogMessage.md#calloutcome)

***

### callType?

> `optional` **callType**: `null` \| [`CallType`](../namespaces/CallLogMessage/enumerations/CallType.md)

Defined in: [WAProto/index.d.ts:21041](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21041)

CallLogMessage callType.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`callType`](../interfaces/ICallLogMessage.md#calltype)

***

### durationSecs?

> `optional` **durationSecs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:21038](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21038)

CallLogMessage durationSecs.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`durationSecs`](../interfaces/ICallLogMessage.md#durationsecs)

***

### isVideo?

> `optional` **isVideo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:21032](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21032)

CallLogMessage isVideo.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`isVideo`](../interfaces/ICallLogMessage.md#isvideo)

***

### participants

> **participants**: [`ICallParticipant`](../namespaces/CallLogMessage/interfaces/ICallParticipant.md)[]

Defined in: [WAProto/index.d.ts:21044](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21044)

CallLogMessage participants.

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`participants`](../interfaces/ICallLogMessage.md#participants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21114](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21114)

Converts this CallLogMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:21051](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21051)

Creates a new CallLogMessage instance using the specified properties.

#### Parameters

##### properties?

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

Properties to set

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:21077](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21077)

Decodes a CallLogMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:21086](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21086)

Decodes a CallLogMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21059](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21059)

Encodes the specified CallLogMessage message. Does not implicitly [verify](CallLogMessage.md#verify) messages.

#### Parameters

##### message

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

CallLogMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21067](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21067)

Encodes the specified CallLogMessage message, length delimited. Does not implicitly [verify](CallLogMessage.md#verify) messages.

#### Parameters

##### message

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

CallLogMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:21100](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21100)

Creates a CallLogMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21121](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21121)

Gets the default type url for CallLogMessage

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

Defined in: [WAProto/index.d.ts:21108](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21108)

Creates a plain object from a CallLogMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`CallLogMessage`](CallLogMessage.md)

CallLogMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21093](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L21093)

Verifies a CallLogMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
