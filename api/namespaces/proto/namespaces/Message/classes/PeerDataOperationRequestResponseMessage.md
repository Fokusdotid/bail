# Class: PeerDataOperationRequestResponseMessage

Defined in: [WAProto/index.d.ts:30025](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30025)

Represents a PeerDataOperationRequestResponseMessage.

## Implements

- [`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

## Constructors

### new PeerDataOperationRequestResponseMessage()

> **new PeerDataOperationRequestResponseMessage**(`properties`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:30031](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30031)

Constructs a new PeerDataOperationRequestResponseMessage.

#### Parameters

##### properties?

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

## Properties

### peerDataOperationRequestType?

> `optional` **peerDataOperationRequestType**: `null` \| [`PeerDataOperationRequestType`](../enumerations/PeerDataOperationRequestType.md)

Defined in: [WAProto/index.d.ts:30034](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30034)

PeerDataOperationRequestResponseMessage peerDataOperationRequestType.

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`peerDataOperationRequestType`](../interfaces/IPeerDataOperationRequestResponseMessage.md#peerdataoperationrequesttype)

***

### peerDataOperationResult

> **peerDataOperationResult**: [`IPeerDataOperationResult`](../namespaces/PeerDataOperationRequestResponseMessage/interfaces/IPeerDataOperationResult.md)[]

Defined in: [WAProto/index.d.ts:30040](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30040)

PeerDataOperationRequestResponseMessage peerDataOperationResult.

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`peerDataOperationResult`](../interfaces/IPeerDataOperationRequestResponseMessage.md#peerdataoperationresult)

***

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30037](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30037)

PeerDataOperationRequestResponseMessage stanzaId.

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`stanzaId`](../interfaces/IPeerDataOperationRequestResponseMessage.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:30110](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30110)

Converts this PeerDataOperationRequestResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:30047](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30047)

Creates a new PeerDataOperationRequestResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:30073](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30073)

Decodes a PeerDataOperationRequestResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:30082](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30082)

Decodes a PeerDataOperationRequestResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30055](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30055)

Encodes the specified PeerDataOperationRequestResponseMessage message. Does not implicitly [verify](PeerDataOperationRequestResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30063](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30063)

Encodes the specified PeerDataOperationRequestResponseMessage message, length delimited. Does not implicitly [verify](PeerDataOperationRequestResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:30096](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30096)

Creates a PeerDataOperationRequestResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:30117](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30117)

Gets the default type url for PeerDataOperationRequestResponseMessage

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

Defined in: [WAProto/index.d.ts:30104](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30104)

Creates a plain object from a PeerDataOperationRequestResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

PeerDataOperationRequestResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:30089](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L30089)

Verifies a PeerDataOperationRequestResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
