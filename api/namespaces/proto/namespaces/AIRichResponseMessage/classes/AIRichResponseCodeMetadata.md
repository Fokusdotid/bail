# Class: AIRichResponseCodeMetadata

Defined in: [WAProto/index.d.ts:818](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L818)

Represents a AIRichResponseCodeMetadata.

## Implements

- [`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

## Constructors

### new AIRichResponseCodeMetadata()

> **new AIRichResponseCodeMetadata**(`properties`?): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:824](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L824)

Constructs a new AIRichResponseCodeMetadata.

#### Parameters

##### properties?

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

Properties to set

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

## Properties

### codeBlocks

> **codeBlocks**: [`IAIRichResponseCodeBlock`](../namespaces/AIRichResponseCodeMetadata/interfaces/IAIRichResponseCodeBlock.md)[]

Defined in: [WAProto/index.d.ts:830](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L830)

AIRichResponseCodeMetadata codeBlocks.

#### Implementation of

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md).[`codeBlocks`](../interfaces/IAIRichResponseCodeMetadata.md#codeblocks)

***

### codeLanguage?

> `optional` **codeLanguage**: `null` \| `string`

Defined in: [WAProto/index.d.ts:827](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L827)

AIRichResponseCodeMetadata codeLanguage.

#### Implementation of

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md).[`codeLanguage`](../interfaces/IAIRichResponseCodeMetadata.md#codelanguage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:900](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L900)

Converts this AIRichResponseCodeMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:837](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L837)

Creates a new AIRichResponseCodeMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

Properties to set

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

AIRichResponseCodeMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:863](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L863)

Decodes a AIRichResponseCodeMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

AIRichResponseCodeMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:872](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L872)

Decodes a AIRichResponseCodeMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

AIRichResponseCodeMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:845](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L845)

Encodes the specified AIRichResponseCodeMetadata message. Does not implicitly [verify](AIRichResponseCodeMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

AIRichResponseCodeMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:853](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L853)

Encodes the specified AIRichResponseCodeMetadata message, length delimited. Does not implicitly [verify](AIRichResponseCodeMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

AIRichResponseCodeMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:886](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L886)

Creates a AIRichResponseCodeMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

AIRichResponseCodeMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:907](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L907)

Gets the default type url for AIRichResponseCodeMetadata

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

Defined in: [WAProto/index.d.ts:894](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L894)

Creates a plain object from a AIRichResponseCodeMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

AIRichResponseCodeMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:879](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L879)

Verifies a AIRichResponseCodeMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
