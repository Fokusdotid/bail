# Class: BotProgressIndicatorMetadata

Defined in: [WAProto/index.d.ts:5561](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5561)

Represents a BotProgressIndicatorMetadata.

## Implements

- [`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

## Constructors

### new BotProgressIndicatorMetadata()

> **new BotProgressIndicatorMetadata**(`properties`?): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:5567](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5567)

Constructs a new BotProgressIndicatorMetadata.

#### Parameters

##### properties?

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

Properties to set

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

## Properties

### progressDescription?

> `optional` **progressDescription**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5570](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5570)

BotProgressIndicatorMetadata progressDescription.

#### Implementation of

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md).[`progressDescription`](../interfaces/IBotProgressIndicatorMetadata.md#progressdescription)

***

### stepsMetadata

> **stepsMetadata**: [`IBotPlanningStepMetadata`](../namespaces/BotProgressIndicatorMetadata/interfaces/IBotPlanningStepMetadata.md)[]

Defined in: [WAProto/index.d.ts:5573](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5573)

BotProgressIndicatorMetadata stepsMetadata.

#### Implementation of

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md).[`stepsMetadata`](../interfaces/IBotProgressIndicatorMetadata.md#stepsmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5643](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5643)

Converts this BotProgressIndicatorMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:5580](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5580)

Creates a new BotProgressIndicatorMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

Properties to set

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

BotProgressIndicatorMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:5606](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5606)

Decodes a BotProgressIndicatorMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

BotProgressIndicatorMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:5615](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5615)

Decodes a BotProgressIndicatorMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

BotProgressIndicatorMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5588](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5588)

Encodes the specified BotProgressIndicatorMetadata message. Does not implicitly [verify](BotProgressIndicatorMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

BotProgressIndicatorMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:5596](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5596)

Encodes the specified BotProgressIndicatorMetadata message, length delimited. Does not implicitly [verify](BotProgressIndicatorMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

BotProgressIndicatorMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:5629](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5629)

Creates a BotProgressIndicatorMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

BotProgressIndicatorMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5650](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5650)

Gets the default type url for BotProgressIndicatorMetadata

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

Defined in: [WAProto/index.d.ts:5637](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5637)

Creates a plain object from a BotProgressIndicatorMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

BotProgressIndicatorMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:5622](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L5622)

Verifies a BotProgressIndicatorMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
