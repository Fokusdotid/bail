# Class: AIRichResponseContentItemMetadata

Defined in: [WAProto/index.d.ts:1139](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1139)

Represents a AIRichResponseContentItemMetadata.

## Implements

- [`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

## Constructors

### new AIRichResponseContentItemMetadata()

> **new AIRichResponseContentItemMetadata**(`properties`?): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:1145](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1145)

Constructs a new AIRichResponseContentItemMetadata.

#### Parameters

##### properties?

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

Properties to set

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

## Properties

### aIRichResponseContentItem?

> `optional` **aIRichResponseContentItem**: `"reelItem"`

Defined in: [WAProto/index.d.ts:1151](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1151)

AIRichResponseContentItemMetadata aIRichResponseContentItem.

***

### reelItem?

> `optional` **reelItem**: `null` \| [`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md)

Defined in: [WAProto/index.d.ts:1148](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1148)

AIRichResponseContentItemMetadata reelItem.

#### Implementation of

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md).[`reelItem`](../interfaces/IAIRichResponseContentItemMetadata.md#reelitem)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1221](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1221)

Converts this AIRichResponseContentItemMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:1158](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1158)

Creates a new AIRichResponseContentItemMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

Properties to set

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

AIRichResponseContentItemMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:1184](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1184)

Decodes a AIRichResponseContentItemMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

AIRichResponseContentItemMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:1193](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1193)

Decodes a AIRichResponseContentItemMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

AIRichResponseContentItemMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1166](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1166)

Encodes the specified AIRichResponseContentItemMetadata message. Does not implicitly [verify](AIRichResponseContentItemMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

AIRichResponseContentItemMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1174](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1174)

Encodes the specified AIRichResponseContentItemMetadata message, length delimited. Does not implicitly [verify](AIRichResponseContentItemMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

AIRichResponseContentItemMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:1207](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1207)

Creates a AIRichResponseContentItemMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

AIRichResponseContentItemMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1228](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1228)

Gets the default type url for AIRichResponseContentItemMetadata

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

Defined in: [WAProto/index.d.ts:1215](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1215)

Creates a plain object from a AIRichResponseContentItemMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

AIRichResponseContentItemMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1200](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L1200)

Verifies a AIRichResponseContentItemMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
