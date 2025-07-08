# Class: AIRichResponseImageURL

Defined in: [WAProto/index.d.ts:1595](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1595)

Represents a AIRichResponseImageURL.

## Implements

- [`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

## Constructors

### new AIRichResponseImageURL()

> **new AIRichResponseImageURL**(`properties`?): [`AIRichResponseImageURL`](AIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:1601](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1601)

Constructs a new AIRichResponseImageURL.

#### Parameters

##### properties?

[`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

Properties to set

#### Returns

[`AIRichResponseImageURL`](AIRichResponseImageURL.md)

## Properties

### imageHighResUrl?

> `optional` **imageHighResUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1607](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1607)

AIRichResponseImageURL imageHighResUrl.

#### Implementation of

[`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md).[`imageHighResUrl`](../interfaces/IAIRichResponseImageURL.md#imagehighresurl)

***

### imagePreviewUrl?

> `optional` **imagePreviewUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1604](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1604)

AIRichResponseImageURL imagePreviewUrl.

#### Implementation of

[`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md).[`imagePreviewUrl`](../interfaces/IAIRichResponseImageURL.md#imagepreviewurl)

***

### sourceUrl?

> `optional` **sourceUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1610](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1610)

AIRichResponseImageURL sourceUrl.

#### Implementation of

[`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md).[`sourceUrl`](../interfaces/IAIRichResponseImageURL.md#sourceurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1680](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1680)

Converts this AIRichResponseImageURL to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseImageURL`](AIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:1617](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1617)

Creates a new AIRichResponseImageURL instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

Properties to set

#### Returns

[`AIRichResponseImageURL`](AIRichResponseImageURL.md)

AIRichResponseImageURL instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseImageURL`](AIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:1643](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1643)

Decodes a AIRichResponseImageURL message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseImageURL`](AIRichResponseImageURL.md)

AIRichResponseImageURL

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseImageURL`](AIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:1652](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1652)

Decodes a AIRichResponseImageURL message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseImageURL`](AIRichResponseImageURL.md)

AIRichResponseImageURL

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1625](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1625)

Encodes the specified AIRichResponseImageURL message. Does not implicitly [verify](AIRichResponseImageURL.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

AIRichResponseImageURL message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1633](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1633)

Encodes the specified AIRichResponseImageURL message, length delimited. Does not implicitly [verify](AIRichResponseImageURL.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

AIRichResponseImageURL message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseImageURL`](AIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:1666](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1666)

Creates a AIRichResponseImageURL message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseImageURL`](AIRichResponseImageURL.md)

AIRichResponseImageURL

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1687](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1687)

Gets the default type url for AIRichResponseImageURL

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

Defined in: [WAProto/index.d.ts:1674](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1674)

Creates a plain object from a AIRichResponseImageURL message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseImageURL`](AIRichResponseImageURL.md)

AIRichResponseImageURL

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1659](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L1659)

Verifies a AIRichResponseImageURL message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
