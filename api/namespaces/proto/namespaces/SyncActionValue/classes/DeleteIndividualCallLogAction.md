# Class: DeleteIndividualCallLogAction

Defined in: [WAProto/index.d.ts:45118](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45118)

Represents a DeleteIndividualCallLogAction.

## Implements

- [`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

## Constructors

### new DeleteIndividualCallLogAction()

> **new DeleteIndividualCallLogAction**(`properties`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:45124](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45124)

Constructs a new DeleteIndividualCallLogAction.

#### Parameters

##### properties?

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

Properties to set

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

## Properties

### isIncoming?

> `optional` **isIncoming**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:45130](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45130)

DeleteIndividualCallLogAction isIncoming.

#### Implementation of

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md).[`isIncoming`](../interfaces/IDeleteIndividualCallLogAction.md#isincoming)

***

### peerJid?

> `optional` **peerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:45127](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45127)

DeleteIndividualCallLogAction peerJid.

#### Implementation of

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md).[`peerJid`](../interfaces/IDeleteIndividualCallLogAction.md#peerjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45200](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45200)

Converts this DeleteIndividualCallLogAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:45137](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45137)

Creates a new DeleteIndividualCallLogAction instance using the specified properties.

#### Parameters

##### properties?

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

Properties to set

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:45163](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45163)

Decodes a DeleteIndividualCallLogAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:45172](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45172)

Decodes a DeleteIndividualCallLogAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45145](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45145)

Encodes the specified DeleteIndividualCallLogAction message. Does not implicitly [verify](DeleteIndividualCallLogAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45153](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45153)

Encodes the specified DeleteIndividualCallLogAction message, length delimited. Does not implicitly [verify](DeleteIndividualCallLogAction.md#verify) messages.

#### Parameters

##### message

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:45186](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45186)

Creates a DeleteIndividualCallLogAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45207](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45207)

Gets the default type url for DeleteIndividualCallLogAction

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

Defined in: [WAProto/index.d.ts:45194](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45194)

Creates a plain object from a DeleteIndividualCallLogAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

DeleteIndividualCallLogAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:45179](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45179)

Verifies a DeleteIndividualCallLogAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
