# Class: AIRichResponseCodeBlock

Defined in: [WAProto/index.d.ts:923](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L923)

Represents a AIRichResponseCodeBlock.

## Implements

- [`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

## Constructors

### new AIRichResponseCodeBlock()

> **new AIRichResponseCodeBlock**(`properties`?): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:929](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L929)

Constructs a new AIRichResponseCodeBlock.

#### Parameters

##### properties?

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

Properties to set

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

## Properties

### codeContent?

> `optional` **codeContent**: `null` \| `string`

Defined in: [WAProto/index.d.ts:935](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L935)

AIRichResponseCodeBlock codeContent.

#### Implementation of

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md).[`codeContent`](../interfaces/IAIRichResponseCodeBlock.md#codecontent)

***

### highlightType?

> `optional` **highlightType**: `null` \| [`AIRichResponseCodeHighlightType`](../enumerations/AIRichResponseCodeHighlightType.md)

Defined in: [WAProto/index.d.ts:932](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L932)

AIRichResponseCodeBlock highlightType.

#### Implementation of

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md).[`highlightType`](../interfaces/IAIRichResponseCodeBlock.md#highlighttype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1005](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1005)

Converts this AIRichResponseCodeBlock to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:942](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L942)

Creates a new AIRichResponseCodeBlock instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

Properties to set

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

AIRichResponseCodeBlock instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:968](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L968)

Decodes a AIRichResponseCodeBlock message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

AIRichResponseCodeBlock

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:977](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L977)

Decodes a AIRichResponseCodeBlock message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

AIRichResponseCodeBlock

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:950](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L950)

Encodes the specified AIRichResponseCodeBlock message. Does not implicitly [verify](AIRichResponseCodeBlock.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

AIRichResponseCodeBlock message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:958](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L958)

Encodes the specified AIRichResponseCodeBlock message, length delimited. Does not implicitly [verify](AIRichResponseCodeBlock.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

AIRichResponseCodeBlock message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:991](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L991)

Creates a AIRichResponseCodeBlock message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

AIRichResponseCodeBlock

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1012](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1012)

Gets the default type url for AIRichResponseCodeBlock

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

Defined in: [WAProto/index.d.ts:999](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L999)

Creates a plain object from a AIRichResponseCodeBlock message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

AIRichResponseCodeBlock

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:984](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L984)

Verifies a AIRichResponseCodeBlock message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
