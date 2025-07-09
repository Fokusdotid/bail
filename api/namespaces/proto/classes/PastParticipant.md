# Class: PastParticipant

Defined in: [WAProto/index.d.ts:37925](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37925)

Represents a PastParticipant.

## Implements

- [`IPastParticipant`](../interfaces/IPastParticipant.md)

## Constructors

### new PastParticipant()

> **new PastParticipant**(`properties`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:37931](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37931)

Constructs a new PastParticipant.

#### Parameters

##### properties?

[`IPastParticipant`](../interfaces/IPastParticipant.md)

Properties to set

#### Returns

[`PastParticipant`](PastParticipant.md)

## Properties

### leaveReason?

> `optional` **leaveReason**: `null` \| [`LeaveReason`](../namespaces/PastParticipant/enumerations/LeaveReason.md)

Defined in: [WAProto/index.d.ts:37937](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37937)

PastParticipant leaveReason.

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`leaveReason`](../interfaces/IPastParticipant.md#leavereason)

***

### leaveTs?

> `optional` **leaveTs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:37940](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37940)

PastParticipant leaveTs.

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`leaveTs`](../interfaces/IPastParticipant.md#leavets)

***

### userJid?

> `optional` **userJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37934](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37934)

PastParticipant userJid.

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`userJid`](../interfaces/IPastParticipant.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:38010](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L38010)

Converts this PastParticipant to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:37947](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37947)

Creates a new PastParticipant instance using the specified properties.

#### Parameters

##### properties?

[`IPastParticipant`](../interfaces/IPastParticipant.md)

Properties to set

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:37973](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37973)

Decodes a PastParticipant message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:37982](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37982)

Decodes a PastParticipant message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37955](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37955)

Encodes the specified PastParticipant message. Does not implicitly [verify](PastParticipant.md#verify) messages.

#### Parameters

##### message

[`IPastParticipant`](../interfaces/IPastParticipant.md)

PastParticipant message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37963](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37963)

Encodes the specified PastParticipant message, length delimited. Does not implicitly [verify](PastParticipant.md#verify) messages.

#### Parameters

##### message

[`IPastParticipant`](../interfaces/IPastParticipant.md)

PastParticipant message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:37996](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37996)

Creates a PastParticipant message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PastParticipant`](PastParticipant.md)

PastParticipant

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:38017](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L38017)

Gets the default type url for PastParticipant

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

Defined in: [WAProto/index.d.ts:38004](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L38004)

Creates a plain object from a PastParticipant message. Also converts values to other types if specified.

#### Parameters

##### message

[`PastParticipant`](PastParticipant.md)

PastParticipant

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:37989](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L37989)

Verifies a PastParticipant message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
