# Class: ScheduledCallCreationMessage

Defined in: [WAProto/index.d.ts:33299](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33299)

Represents a ScheduledCallCreationMessage.

## Implements

- [`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

## Constructors

### new ScheduledCallCreationMessage()

> **new ScheduledCallCreationMessage**(`properties`?): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:33305](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33305)

Constructs a new ScheduledCallCreationMessage.

#### Parameters

##### properties?

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

Properties to set

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

## Properties

### callType?

> `optional` **callType**: `null` \| [`CallType`](../namespaces/ScheduledCallCreationMessage/enumerations/CallType.md)

Defined in: [WAProto/index.d.ts:33311](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33311)

ScheduledCallCreationMessage callType.

#### Implementation of

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md).[`callType`](../interfaces/IScheduledCallCreationMessage.md#calltype)

***

### scheduledTimestampMs?

> `optional` **scheduledTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:33308](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33308)

ScheduledCallCreationMessage scheduledTimestampMs.

#### Implementation of

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md).[`scheduledTimestampMs`](../interfaces/IScheduledCallCreationMessage.md#scheduledtimestampms)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:33314](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33314)

ScheduledCallCreationMessage title.

#### Implementation of

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md).[`title`](../interfaces/IScheduledCallCreationMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33384](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33384)

Converts this ScheduledCallCreationMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:33321](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33321)

Creates a new ScheduledCallCreationMessage instance using the specified properties.

#### Parameters

##### properties?

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

Properties to set

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:33347](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33347)

Decodes a ScheduledCallCreationMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:33356](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33356)

Decodes a ScheduledCallCreationMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33329](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33329)

Encodes the specified ScheduledCallCreationMessage message. Does not implicitly [verify](ScheduledCallCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

ScheduledCallCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33337](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33337)

Encodes the specified ScheduledCallCreationMessage message, length delimited. Does not implicitly [verify](ScheduledCallCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IScheduledCallCreationMessage`](../interfaces/IScheduledCallCreationMessage.md)

ScheduledCallCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

Defined in: [WAProto/index.d.ts:33370](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33370)

Creates a ScheduledCallCreationMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:33391](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33391)

Gets the default type url for ScheduledCallCreationMessage

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

Defined in: [WAProto/index.d.ts:33378](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33378)

Creates a plain object from a ScheduledCallCreationMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ScheduledCallCreationMessage`](ScheduledCallCreationMessage.md)

ScheduledCallCreationMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33363](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L33363)

Verifies a ScheduledCallCreationMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
