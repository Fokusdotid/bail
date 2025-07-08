# Class: CtwaPerCustomerDataSharingAction

Defined in: [WAProto/index.d.ts:44606](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44606)

Represents a CtwaPerCustomerDataSharingAction.

## Implements

- [`ICtwaPerCustomerDataSharingAction`](../interfaces/ICtwaPerCustomerDataSharingAction.md)

## Constructors

### new CtwaPerCustomerDataSharingAction()

> **new CtwaPerCustomerDataSharingAction**(`properties`?): [`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

Defined in: [WAProto/index.d.ts:44612](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44612)

Constructs a new CtwaPerCustomerDataSharingAction.

#### Parameters

##### properties?

[`ICtwaPerCustomerDataSharingAction`](../interfaces/ICtwaPerCustomerDataSharingAction.md)

Properties to set

#### Returns

[`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

## Properties

### isCtwaPerCustomerDataSharingEnabled?

> `optional` **isCtwaPerCustomerDataSharingEnabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:44615](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44615)

CtwaPerCustomerDataSharingAction isCtwaPerCustomerDataSharingEnabled.

#### Implementation of

[`ICtwaPerCustomerDataSharingAction`](../interfaces/ICtwaPerCustomerDataSharingAction.md).[`isCtwaPerCustomerDataSharingEnabled`](../interfaces/ICtwaPerCustomerDataSharingAction.md#isctwapercustomerdatasharingenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:44685](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44685)

Converts this CtwaPerCustomerDataSharingAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

Defined in: [WAProto/index.d.ts:44622](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44622)

Creates a new CtwaPerCustomerDataSharingAction instance using the specified properties.

#### Parameters

##### properties?

[`ICtwaPerCustomerDataSharingAction`](../interfaces/ICtwaPerCustomerDataSharingAction.md)

Properties to set

#### Returns

[`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

CtwaPerCustomerDataSharingAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

Defined in: [WAProto/index.d.ts:44648](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44648)

Decodes a CtwaPerCustomerDataSharingAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

CtwaPerCustomerDataSharingAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

Defined in: [WAProto/index.d.ts:44657](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44657)

Decodes a CtwaPerCustomerDataSharingAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

CtwaPerCustomerDataSharingAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44630](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44630)

Encodes the specified CtwaPerCustomerDataSharingAction message. Does not implicitly [verify](CtwaPerCustomerDataSharingAction.md#verify) messages.

#### Parameters

##### message

[`ICtwaPerCustomerDataSharingAction`](../interfaces/ICtwaPerCustomerDataSharingAction.md)

CtwaPerCustomerDataSharingAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44638](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44638)

Encodes the specified CtwaPerCustomerDataSharingAction message, length delimited. Does not implicitly [verify](CtwaPerCustomerDataSharingAction.md#verify) messages.

#### Parameters

##### message

[`ICtwaPerCustomerDataSharingAction`](../interfaces/ICtwaPerCustomerDataSharingAction.md)

CtwaPerCustomerDataSharingAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

Defined in: [WAProto/index.d.ts:44671](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44671)

Creates a CtwaPerCustomerDataSharingAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

CtwaPerCustomerDataSharingAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:44692](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44692)

Gets the default type url for CtwaPerCustomerDataSharingAction

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

Defined in: [WAProto/index.d.ts:44679](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44679)

Creates a plain object from a CtwaPerCustomerDataSharingAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`CtwaPerCustomerDataSharingAction`](CtwaPerCustomerDataSharingAction.md)

CtwaPerCustomerDataSharingAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44664](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L44664)

Verifies a CtwaPerCustomerDataSharingAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
