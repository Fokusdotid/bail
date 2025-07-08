# Class: AIRichResponseTableRow

Defined in: [WAProto/index.d.ts:2598](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2598)

Represents a AIRichResponseTableRow.

## Implements

- [`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

## Constructors

### new AIRichResponseTableRow()

> **new AIRichResponseTableRow**(`properties`?): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:2604](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2604)

Constructs a new AIRichResponseTableRow.

#### Parameters

##### properties?

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

Properties to set

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

## Properties

### isHeading?

> `optional` **isHeading**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2610](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2610)

AIRichResponseTableRow isHeading.

#### Implementation of

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md).[`isHeading`](../interfaces/IAIRichResponseTableRow.md#isheading)

***

### items

> **items**: `string`[]

Defined in: [WAProto/index.d.ts:2607](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2607)

AIRichResponseTableRow items.

#### Implementation of

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md).[`items`](../interfaces/IAIRichResponseTableRow.md#items)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2680](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2680)

Converts this AIRichResponseTableRow to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:2617](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2617)

Creates a new AIRichResponseTableRow instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

Properties to set

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

AIRichResponseTableRow instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:2643](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2643)

Decodes a AIRichResponseTableRow message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

AIRichResponseTableRow

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:2652](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2652)

Decodes a AIRichResponseTableRow message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

AIRichResponseTableRow

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2625](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2625)

Encodes the specified AIRichResponseTableRow message. Does not implicitly [verify](AIRichResponseTableRow.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

AIRichResponseTableRow message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2633](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2633)

Encodes the specified AIRichResponseTableRow message, length delimited. Does not implicitly [verify](AIRichResponseTableRow.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

AIRichResponseTableRow message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:2666](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2666)

Creates a AIRichResponseTableRow message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

AIRichResponseTableRow

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2687](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2687)

Gets the default type url for AIRichResponseTableRow

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

Defined in: [WAProto/index.d.ts:2674](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2674)

Creates a plain object from a AIRichResponseTableRow message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

AIRichResponseTableRow

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2659](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2659)

Verifies a AIRichResponseTableRow message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
