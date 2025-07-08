# Class: PastParticipants

Defined in: [WAProto/index.d.ts:38040](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38040)

Represents a PastParticipants.

## Implements

- [`IPastParticipants`](../interfaces/IPastParticipants.md)

## Constructors

### new PastParticipants()

> **new PastParticipants**(`properties`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:38046](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38046)

Constructs a new PastParticipants.

#### Parameters

##### properties?

[`IPastParticipants`](../interfaces/IPastParticipants.md)

Properties to set

#### Returns

[`PastParticipants`](PastParticipants.md)

## Properties

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:38049](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38049)

PastParticipants groupJid.

#### Implementation of

[`IPastParticipants`](../interfaces/IPastParticipants.md).[`groupJid`](../interfaces/IPastParticipants.md#groupjid)

***

### pastParticipants

> **pastParticipants**: [`IPastParticipant`](../interfaces/IPastParticipant.md)[]

Defined in: [WAProto/index.d.ts:38052](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38052)

PastParticipants pastParticipants.

#### Implementation of

[`IPastParticipants`](../interfaces/IPastParticipants.md).[`pastParticipants`](../interfaces/IPastParticipants.md#pastparticipants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:38122](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38122)

Converts this PastParticipants to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:38059](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38059)

Creates a new PastParticipants instance using the specified properties.

#### Parameters

##### properties?

[`IPastParticipants`](../interfaces/IPastParticipants.md)

Properties to set

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:38085](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38085)

Decodes a PastParticipants message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:38094](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38094)

Decodes a PastParticipants message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38067](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38067)

Encodes the specified PastParticipants message. Does not implicitly [verify](PastParticipants.md#verify) messages.

#### Parameters

##### message

[`IPastParticipants`](../interfaces/IPastParticipants.md)

PastParticipants message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38075](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38075)

Encodes the specified PastParticipants message, length delimited. Does not implicitly [verify](PastParticipants.md#verify) messages.

#### Parameters

##### message

[`IPastParticipants`](../interfaces/IPastParticipants.md)

PastParticipants message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:38108](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38108)

Creates a PastParticipants message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PastParticipants`](PastParticipants.md)

PastParticipants

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:38129](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38129)

Gets the default type url for PastParticipants

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

Defined in: [WAProto/index.d.ts:38116](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38116)

Creates a plain object from a PastParticipants message. Also converts values to other types if specified.

#### Parameters

##### message

[`PastParticipants`](PastParticipants.md)

PastParticipants

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:38101](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38101)

Verifies a PastParticipants message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
