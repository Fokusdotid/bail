# Class: CallLogRecord

Defined in: [WAProto/index.d.ts:7543](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7543)

Represents a CallLogRecord.

## Implements

- [`ICallLogRecord`](../interfaces/ICallLogRecord.md)

## Constructors

### new CallLogRecord()

> **new CallLogRecord**(`properties`?): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:7549](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7549)

Constructs a new CallLogRecord.

#### Parameters

##### properties?

[`ICallLogRecord`](../interfaces/ICallLogRecord.md)

Properties to set

#### Returns

[`CallLogRecord`](CallLogRecord.md)

## Properties

### callCreatorJid?

> `optional` **callCreatorJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7585](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7585)

CallLogRecord callCreatorJid.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callCreatorJid`](../interfaces/ICallLogRecord.md#callcreatorjid)

***

### callId?

> `optional` **callId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7582](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7582)

CallLogRecord callId.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callId`](../interfaces/ICallLogRecord.md#callid)

***

### callLinkToken?

> `optional` **callLinkToken**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7576](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7576)

CallLogRecord callLinkToken.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callLinkToken`](../interfaces/ICallLogRecord.md#calllinktoken)

***

### callResult?

> `optional` **callResult**: `null` \| [`CallResult`](../namespaces/CallLogRecord/enumerations/CallResult.md)

Defined in: [WAProto/index.d.ts:7552](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7552)

CallLogRecord callResult.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callResult`](../interfaces/ICallLogRecord.md#callresult)

***

### callType?

> `optional` **callType**: `null` \| [`CallType`](../namespaces/CallLogRecord/enumerations/CallType.md)

Defined in: [WAProto/index.d.ts:7594](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7594)

CallLogRecord callType.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callType`](../interfaces/ICallLogRecord.md#calltype)

***

### duration?

> `optional` **duration**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7561](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7561)

CallLogRecord duration.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`duration`](../interfaces/ICallLogRecord.md#duration)

***

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7588](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7588)

CallLogRecord groupJid.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`groupJid`](../interfaces/ICallLogRecord.md#groupjid)

***

### isCallLink?

> `optional` **isCallLink**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:7573](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7573)

CallLogRecord isCallLink.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isCallLink`](../interfaces/ICallLogRecord.md#iscalllink)

***

### isDndMode?

> `optional` **isDndMode**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:7555](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7555)

CallLogRecord isDndMode.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isDndMode`](../interfaces/ICallLogRecord.md#isdndmode)

***

### isIncoming?

> `optional` **isIncoming**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:7567](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7567)

CallLogRecord isIncoming.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isIncoming`](../interfaces/ICallLogRecord.md#isincoming)

***

### isVideo?

> `optional` **isVideo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:7570](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7570)

CallLogRecord isVideo.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isVideo`](../interfaces/ICallLogRecord.md#isvideo)

***

### participants

> **participants**: [`IParticipantInfo`](../namespaces/CallLogRecord/interfaces/IParticipantInfo.md)[]

Defined in: [WAProto/index.d.ts:7591](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7591)

CallLogRecord participants.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`participants`](../interfaces/ICallLogRecord.md#participants)

***

### scheduledCallId?

> `optional` **scheduledCallId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7579](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7579)

CallLogRecord scheduledCallId.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`scheduledCallId`](../interfaces/ICallLogRecord.md#scheduledcallid)

***

### silenceReason?

> `optional` **silenceReason**: `null` \| [`SilenceReason`](../namespaces/CallLogRecord/enumerations/SilenceReason.md)

Defined in: [WAProto/index.d.ts:7558](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7558)

CallLogRecord silenceReason.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`silenceReason`](../interfaces/ICallLogRecord.md#silencereason)

***

### startTime?

> `optional` **startTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7564](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7564)

CallLogRecord startTime.

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`startTime`](../interfaces/ICallLogRecord.md#starttime)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7664](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7664)

Converts this CallLogRecord to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:7601](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7601)

Creates a new CallLogRecord instance using the specified properties.

#### Parameters

##### properties?

[`ICallLogRecord`](../interfaces/ICallLogRecord.md)

Properties to set

#### Returns

[`CallLogRecord`](CallLogRecord.md)

CallLogRecord instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:7627](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7627)

Decodes a CallLogRecord message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CallLogRecord`](CallLogRecord.md)

CallLogRecord

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:7636](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7636)

Decodes a CallLogRecord message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CallLogRecord`](CallLogRecord.md)

CallLogRecord

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7609](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7609)

Encodes the specified CallLogRecord message. Does not implicitly [verify](CallLogRecord.md#verify) messages.

#### Parameters

##### message

[`ICallLogRecord`](../interfaces/ICallLogRecord.md)

CallLogRecord message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:7617](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7617)

Encodes the specified CallLogRecord message, length delimited. Does not implicitly [verify](CallLogRecord.md#verify) messages.

#### Parameters

##### message

[`ICallLogRecord`](../interfaces/ICallLogRecord.md)

CallLogRecord message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:7650](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7650)

Creates a CallLogRecord message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CallLogRecord`](CallLogRecord.md)

CallLogRecord

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7671](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7671)

Gets the default type url for CallLogRecord

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

Defined in: [WAProto/index.d.ts:7658](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7658)

Creates a plain object from a CallLogRecord message. Also converts values to other types if specified.

#### Parameters

##### message

[`CallLogRecord`](CallLogRecord.md)

CallLogRecord

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:7643](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L7643)

Verifies a CallLogRecord message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
