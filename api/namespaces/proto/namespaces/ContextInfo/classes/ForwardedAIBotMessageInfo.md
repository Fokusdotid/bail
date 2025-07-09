# Class: ForwardedAIBotMessageInfo

Defined in: [WAProto/index.d.ts:11953](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11953)

Represents a ForwardedAIBotMessageInfo.

## Implements

- [`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

## Constructors

### new ForwardedAIBotMessageInfo()

> **new ForwardedAIBotMessageInfo**(`properties`?): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:11959](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11959)

Constructs a new ForwardedAIBotMessageInfo.

#### Parameters

##### properties?

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

Properties to set

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

## Properties

### botJid?

> `optional` **botJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11965](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11965)

ForwardedAIBotMessageInfo botJid.

#### Implementation of

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md).[`botJid`](../interfaces/IForwardedAIBotMessageInfo.md#botjid)

***

### botName?

> `optional` **botName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11962](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11962)

ForwardedAIBotMessageInfo botName.

#### Implementation of

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md).[`botName`](../interfaces/IForwardedAIBotMessageInfo.md#botname)

***

### creatorName?

> `optional` **creatorName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11968](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11968)

ForwardedAIBotMessageInfo creatorName.

#### Implementation of

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md).[`creatorName`](../interfaces/IForwardedAIBotMessageInfo.md#creatorname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12038](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L12038)

Converts this ForwardedAIBotMessageInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:11975](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11975)

Creates a new ForwardedAIBotMessageInfo instance using the specified properties.

#### Parameters

##### properties?

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

Properties to set

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

ForwardedAIBotMessageInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:12001](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L12001)

Decodes a ForwardedAIBotMessageInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

ForwardedAIBotMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:12010](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L12010)

Decodes a ForwardedAIBotMessageInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

ForwardedAIBotMessageInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11983](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11983)

Encodes the specified ForwardedAIBotMessageInfo message. Does not implicitly [verify](ForwardedAIBotMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

ForwardedAIBotMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:11991](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L11991)

Encodes the specified ForwardedAIBotMessageInfo message, length delimited. Does not implicitly [verify](ForwardedAIBotMessageInfo.md#verify) messages.

#### Parameters

##### message

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

ForwardedAIBotMessageInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:12024](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L12024)

Creates a ForwardedAIBotMessageInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

ForwardedAIBotMessageInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12045](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L12045)

Gets the default type url for ForwardedAIBotMessageInfo

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

Defined in: [WAProto/index.d.ts:12032](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L12032)

Creates a plain object from a ForwardedAIBotMessageInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

ForwardedAIBotMessageInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12017](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L12017)

Verifies a ForwardedAIBotMessageInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
