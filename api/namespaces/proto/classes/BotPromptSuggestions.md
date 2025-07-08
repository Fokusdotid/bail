# Class: BotPromptSuggestions

Defined in: [WAProto/index.d.ts:6375](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6375)

Represents a BotPromptSuggestions.

## Implements

- [`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

## Constructors

### new BotPromptSuggestions()

> **new BotPromptSuggestions**(`properties`?): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:6381](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6381)

Constructs a new BotPromptSuggestions.

#### Parameters

##### properties?

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

Properties to set

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

## Properties

### suggestions

> **suggestions**: [`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md)[]

Defined in: [WAProto/index.d.ts:6384](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6384)

BotPromptSuggestions suggestions.

#### Implementation of

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md).[`suggestions`](../interfaces/IBotPromptSuggestions.md#suggestions)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6454](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6454)

Converts this BotPromptSuggestions to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:6391](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6391)

Creates a new BotPromptSuggestions instance using the specified properties.

#### Parameters

##### properties?

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

Properties to set

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

BotPromptSuggestions instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:6417](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6417)

Decodes a BotPromptSuggestions message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

BotPromptSuggestions

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:6426](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6426)

Decodes a BotPromptSuggestions message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

BotPromptSuggestions

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6399](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6399)

Encodes the specified BotPromptSuggestions message. Does not implicitly [verify](BotPromptSuggestions.md#verify) messages.

#### Parameters

##### message

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

BotPromptSuggestions message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6407](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6407)

Encodes the specified BotPromptSuggestions message, length delimited. Does not implicitly [verify](BotPromptSuggestions.md#verify) messages.

#### Parameters

##### message

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

BotPromptSuggestions message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:6440](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6440)

Creates a BotPromptSuggestions message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

BotPromptSuggestions

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6461](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6461)

Gets the default type url for BotPromptSuggestions

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

Defined in: [WAProto/index.d.ts:6448](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6448)

Creates a plain object from a BotPromptSuggestions message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotPromptSuggestions`](BotPromptSuggestions.md)

BotPromptSuggestions

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6433](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6433)

Verifies a BotPromptSuggestions message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
