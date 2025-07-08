# Class: AIRichResponseDynamicMetadata

Defined in: [WAProto/index.d.ts:1370](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1370)

Represents a AIRichResponseDynamicMetadata.

## Implements

- [`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

## Constructors

### new AIRichResponseDynamicMetadata()

> **new AIRichResponseDynamicMetadata**(`properties`?): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:1376](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1376)

Constructs a new AIRichResponseDynamicMetadata.

#### Parameters

##### properties?

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

Properties to set

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

## Properties

### loopCount?

> `optional` **loopCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:1388](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1388)

AIRichResponseDynamicMetadata loopCount.

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`loopCount`](../interfaces/IAIRichResponseDynamicMetadata.md#loopcount)

***

### type?

> `optional` **type**: `null` \| [`AIRichResponseDynamicMetadataType`](../namespaces/AIRichResponseDynamicMetadata/enumerations/AIRichResponseDynamicMetadataType.md)

Defined in: [WAProto/index.d.ts:1379](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1379)

AIRichResponseDynamicMetadata type.

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`type`](../interfaces/IAIRichResponseDynamicMetadata.md#type)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1385](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1385)

AIRichResponseDynamicMetadata url.

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`url`](../interfaces/IAIRichResponseDynamicMetadata.md#url)

***

### version?

> `optional` **version**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:1382](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1382)

AIRichResponseDynamicMetadata version.

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`version`](../interfaces/IAIRichResponseDynamicMetadata.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1458](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1458)

Converts this AIRichResponseDynamicMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:1395](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1395)

Creates a new AIRichResponseDynamicMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

Properties to set

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

AIRichResponseDynamicMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:1421](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1421)

Decodes a AIRichResponseDynamicMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

AIRichResponseDynamicMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:1430](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1430)

Decodes a AIRichResponseDynamicMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

AIRichResponseDynamicMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1403](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1403)

Encodes the specified AIRichResponseDynamicMetadata message. Does not implicitly [verify](AIRichResponseDynamicMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

AIRichResponseDynamicMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:1411](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1411)

Encodes the specified AIRichResponseDynamicMetadata message, length delimited. Does not implicitly [verify](AIRichResponseDynamicMetadata.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

AIRichResponseDynamicMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:1444](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1444)

Creates a AIRichResponseDynamicMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

AIRichResponseDynamicMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1465](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1465)

Gets the default type url for AIRichResponseDynamicMetadata

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

Defined in: [WAProto/index.d.ts:1452](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1452)

Creates a plain object from a AIRichResponseDynamicMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

AIRichResponseDynamicMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:1437](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L1437)

Verifies a AIRichResponseDynamicMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
