# Class: EventMessage

Defined in: [WAProto/index.d.ts:22789](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22789)

Represents an EventMessage.

## Implements

- [`IEventMessage`](../interfaces/IEventMessage.md)

## Constructors

### new EventMessage()

> **new EventMessage**(`properties`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:22795](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22795)

Constructs a new EventMessage.

#### Parameters

##### properties?

[`IEventMessage`](../interfaces/IEventMessage.md)

Properties to set

#### Returns

[`EventMessage`](EventMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:22798](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22798)

EventMessage contextInfo.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`contextInfo`](../interfaces/IEventMessage.md#contextinfo)

***

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:22807](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22807)

EventMessage description.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`description`](../interfaces/IEventMessage.md#description)

***

### endTime?

> `optional` **endTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:22819](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22819)

EventMessage endTime.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`endTime`](../interfaces/IEventMessage.md#endtime)

***

### extraGuestsAllowed?

> `optional` **extraGuestsAllowed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:22822](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22822)

EventMessage extraGuestsAllowed.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`extraGuestsAllowed`](../interfaces/IEventMessage.md#extraguestsallowed)

***

### isCanceled?

> `optional` **isCanceled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:22801](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22801)

EventMessage isCanceled.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`isCanceled`](../interfaces/IEventMessage.md#iscanceled)

***

### isScheduleCall?

> `optional` **isScheduleCall**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:22825](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22825)

EventMessage isScheduleCall.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`isScheduleCall`](../interfaces/IEventMessage.md#isschedulecall)

***

### joinLink?

> `optional` **joinLink**: `null` \| `string`

Defined in: [WAProto/index.d.ts:22813](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22813)

EventMessage joinLink.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`joinLink`](../interfaces/IEventMessage.md#joinlink)

***

### location?

> `optional` **location**: `null` \| [`ILocationMessage`](../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:22810](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22810)

EventMessage location.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`location`](../interfaces/IEventMessage.md#location)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:22804](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22804)

EventMessage name.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`name`](../interfaces/IEventMessage.md#name)

***

### startTime?

> `optional` **startTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:22816](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22816)

EventMessage startTime.

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`startTime`](../interfaces/IEventMessage.md#starttime)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:22895](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22895)

Converts this EventMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:22832](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22832)

Creates a new EventMessage instance using the specified properties.

#### Parameters

##### properties?

[`IEventMessage`](../interfaces/IEventMessage.md)

Properties to set

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:22858](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22858)

Decodes an EventMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:22867](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22867)

Decodes an EventMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22840](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22840)

Encodes the specified EventMessage message. Does not implicitly [verify](EventMessage.md#verify) messages.

#### Parameters

##### message

[`IEventMessage`](../interfaces/IEventMessage.md)

EventMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:22848](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22848)

Encodes the specified EventMessage message, length delimited. Does not implicitly [verify](EventMessage.md#verify) messages.

#### Parameters

##### message

[`IEventMessage`](../interfaces/IEventMessage.md)

EventMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:22881](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22881)

Creates an EventMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EventMessage`](EventMessage.md)

EventMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:22902](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22902)

Gets the default type url for EventMessage

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

Defined in: [WAProto/index.d.ts:22889](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22889)

Creates a plain object from an EventMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`EventMessage`](EventMessage.md)

EventMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:22874](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L22874)

Verifies an EventMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
