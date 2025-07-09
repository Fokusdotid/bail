# Class: ClearChatAction

Defined in: [WAProto/index.d.ts:44382](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44382)

Represents a ClearChatAction.

## Implements

- [`IClearChatAction`](../interfaces/IClearChatAction.md)

## Constructors

### new ClearChatAction()

> **new ClearChatAction**(`properties`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:44388](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44388)

Constructs a new ClearChatAction.

#### Parameters

##### properties?

[`IClearChatAction`](../interfaces/IClearChatAction.md)

Properties to set

#### Returns

[`ClearChatAction`](ClearChatAction.md)

## Properties

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:44391](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44391)

ClearChatAction messageRange.

#### Implementation of

[`IClearChatAction`](../interfaces/IClearChatAction.md).[`messageRange`](../interfaces/IClearChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:44461](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44461)

Converts this ClearChatAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:44398](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44398)

Creates a new ClearChatAction instance using the specified properties.

#### Parameters

##### properties?

[`IClearChatAction`](../interfaces/IClearChatAction.md)

Properties to set

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:44424](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44424)

Decodes a ClearChatAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:44433](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44433)

Decodes a ClearChatAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44406](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44406)

Encodes the specified ClearChatAction message. Does not implicitly [verify](ClearChatAction.md#verify) messages.

#### Parameters

##### message

[`IClearChatAction`](../interfaces/IClearChatAction.md)

ClearChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44414](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44414)

Encodes the specified ClearChatAction message, length delimited. Does not implicitly [verify](ClearChatAction.md#verify) messages.

#### Parameters

##### message

[`IClearChatAction`](../interfaces/IClearChatAction.md)

ClearChatAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:44447](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44447)

Creates a ClearChatAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:44468](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44468)

Gets the default type url for ClearChatAction

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

Defined in: [WAProto/index.d.ts:44455](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44455)

Creates a plain object from a ClearChatAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ClearChatAction`](ClearChatAction.md)

ClearChatAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44440](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L44440)

Verifies a ClearChatAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
