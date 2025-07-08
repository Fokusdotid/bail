# Class: AIRichResponseGridImageMetadata

Defined in: [WAProto/index.d.ts:1489](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1489)

Represents a AIRichResponseGridImageMetadata.

## Implements

- [`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

## Constructors

### new AIRichResponseGridImageMetadata()

> **new AIRichResponseGridImageMetadata**(`properties`?): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:1495](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1495)

Constructs a new AIRichResponseGridImageMetadata.

#### Parameters

##### properties?

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

Properties to set

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

## Properties

### gridImageUrl?

> `optional` **gridImageUrl**: `null` \| [`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:1498](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1498)

AIRichResponseGridImageMetadata gridImageUrl.

#### Implementation of

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md).[`gridImageUrl`](../interfaces/IAIRichResponseGridImageMetadata.md#gridimageurl)

***

### imageUrls

> **imageUrls**: [`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)[]

Defined in: [WAProto/index.d.ts:1501](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1501)

AIRichResponseGridImageMetadata imageUrls.

#### Implementation of

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md).[`imageUrls`](../interfaces/IAIRichResponseGridImageMetadata.md#imageurls)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1571](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1571)

Converts this AIRichResponseGridImageMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:1508](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1508)

Creates a new AIRichResponseGridImageMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

Properties to set

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

AIRichResponseGridImageMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:1534](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1534)

Decodes a AIRichResponseGridImageMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

AIRichResponseGridImageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:1543](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1543)

Decodes a AIRichResponseGridImageMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

AIRichResponseGridImageMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1516](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1516)

Encodes the specified AIRichResponseGridImageMetadata message. Does not implicitly [verify](AIRichResponseGridImageMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

AIRichResponseGridImageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1524](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1524)

Encodes the specified AIRichResponseGridImageMetadata message, length delimited. Does not implicitly [verify](AIRichResponseGridImageMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

AIRichResponseGridImageMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:1557](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1557)

Creates a AIRichResponseGridImageMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

AIRichResponseGridImageMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1578](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1578)

Gets the default type url for AIRichResponseGridImageMetadata

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

Defined in: [WAProto/index.d.ts:1565](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1565)

Creates a plain object from a AIRichResponseGridImageMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

AIRichResponseGridImageMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1550](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L1550)

Verifies a AIRichResponseGridImageMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
