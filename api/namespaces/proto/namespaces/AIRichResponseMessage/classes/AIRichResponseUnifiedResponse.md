# Class: AIRichResponseUnifiedResponse

Defined in: [WAProto/index.d.ts:2699](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2699)

Represents a AIRichResponseUnifiedResponse.

## Implements

- [`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

## Constructors

### new AIRichResponseUnifiedResponse()

> **new AIRichResponseUnifiedResponse**(`properties`?): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:2705](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2705)

Constructs a new AIRichResponseUnifiedResponse.

#### Parameters

##### properties?

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

Properties to set

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

## Properties

### data?

> `optional` **data**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2708](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2708)

AIRichResponseUnifiedResponse data.

#### Implementation of

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md).[`data`](../interfaces/IAIRichResponseUnifiedResponse.md#data)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2778](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2778)

Converts this AIRichResponseUnifiedResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:2715](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2715)

Creates a new AIRichResponseUnifiedResponse instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

Properties to set

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

AIRichResponseUnifiedResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:2741](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2741)

Decodes a AIRichResponseUnifiedResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

AIRichResponseUnifiedResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:2750](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2750)

Decodes a AIRichResponseUnifiedResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

AIRichResponseUnifiedResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2723](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2723)

Encodes the specified AIRichResponseUnifiedResponse message. Does not implicitly [verify](AIRichResponseUnifiedResponse.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

AIRichResponseUnifiedResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2731](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2731)

Encodes the specified AIRichResponseUnifiedResponse message, length delimited. Does not implicitly [verify](AIRichResponseUnifiedResponse.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

AIRichResponseUnifiedResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:2764](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2764)

Creates a AIRichResponseUnifiedResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

AIRichResponseUnifiedResponse

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2785](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2785)

Gets the default type url for AIRichResponseUnifiedResponse

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

Defined in: [WAProto/index.d.ts:2772](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2772)

Creates a plain object from a AIRichResponseUnifiedResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

AIRichResponseUnifiedResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2757](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2757)

Verifies a AIRichResponseUnifiedResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
