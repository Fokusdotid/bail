# Class: SenderKeyDistributionMessage

Defined in: [WAProto/index.d.ts:33761](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33761)

Represents a SenderKeyDistributionMessage.

## Implements

- [`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

## Constructors

### new SenderKeyDistributionMessage()

> **new SenderKeyDistributionMessage**(`properties`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:33767](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33767)

Constructs a new SenderKeyDistributionMessage.

#### Parameters

##### properties?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

Properties to set

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

## Properties

### axolotlSenderKeyDistributionMessage?

> `optional` **axolotlSenderKeyDistributionMessage**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:33773](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33773)

SenderKeyDistributionMessage axolotlSenderKeyDistributionMessage.

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`axolotlSenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md#axolotlsenderkeydistributionmessage)

***

### groupId?

> `optional` **groupId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:33770](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33770)

SenderKeyDistributionMessage groupId.

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`groupId`](../interfaces/ISenderKeyDistributionMessage.md#groupid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33843](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33843)

Converts this SenderKeyDistributionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:33780](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33780)

Creates a new SenderKeyDistributionMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

Properties to set

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:33806](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33806)

Decodes a SenderKeyDistributionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:33815](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33815)

Decodes a SenderKeyDistributionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33788](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33788)

Encodes the specified SenderKeyDistributionMessage message. Does not implicitly [verify](SenderKeyDistributionMessage.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

SenderKeyDistributionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33796](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33796)

Encodes the specified SenderKeyDistributionMessage message, length delimited. Does not implicitly [verify](SenderKeyDistributionMessage.md#verify) messages.

#### Parameters

##### message

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

SenderKeyDistributionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:33829](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33829)

Creates a SenderKeyDistributionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:33850](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33850)

Gets the default type url for SenderKeyDistributionMessage

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

Defined in: [WAProto/index.d.ts:33837](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33837)

Creates a plain object from a SenderKeyDistributionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

SenderKeyDistributionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33822](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L33822)

Verifies a SenderKeyDistributionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
