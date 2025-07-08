# Class: ExternalWebBetaAction

Defined in: [WAProto/index.d.ts:45321](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45321)

Represents an ExternalWebBetaAction.

## Implements

- [`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

## Constructors

### new ExternalWebBetaAction()

> **new ExternalWebBetaAction**(`properties`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:45327](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45327)

Constructs a new ExternalWebBetaAction.

#### Parameters

##### properties?

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

Properties to set

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

## Properties

### isOptIn?

> `optional` **isOptIn**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:45330](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45330)

ExternalWebBetaAction isOptIn.

#### Implementation of

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md).[`isOptIn`](../interfaces/IExternalWebBetaAction.md#isoptin)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45400](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45400)

Converts this ExternalWebBetaAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:45337](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45337)

Creates a new ExternalWebBetaAction instance using the specified properties.

#### Parameters

##### properties?

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

Properties to set

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:45363](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45363)

Decodes an ExternalWebBetaAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:45372](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45372)

Decodes an ExternalWebBetaAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45345](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45345)

Encodes the specified ExternalWebBetaAction message. Does not implicitly [verify](ExternalWebBetaAction.md#verify) messages.

#### Parameters

##### message

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

ExternalWebBetaAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45353](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45353)

Encodes the specified ExternalWebBetaAction message, length delimited. Does not implicitly [verify](ExternalWebBetaAction.md#verify) messages.

#### Parameters

##### message

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

ExternalWebBetaAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:45386](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45386)

Creates an ExternalWebBetaAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45407](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45407)

Gets the default type url for ExternalWebBetaAction

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

Defined in: [WAProto/index.d.ts:45394](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45394)

Creates a plain object from an ExternalWebBetaAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

ExternalWebBetaAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:45379](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L45379)

Verifies an ExternalWebBetaAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
