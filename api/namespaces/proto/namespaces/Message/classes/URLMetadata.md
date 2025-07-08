# Class: URLMetadata

Defined in: [WAProto/index.d.ts:35210](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35210)

Represents a URLMetadata.

## Implements

- [`IURLMetadata`](../interfaces/IURLMetadata.md)

## Constructors

### new URLMetadata()

> **new URLMetadata**(`properties`?): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:35216](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35216)

Constructs a new URLMetadata.

#### Parameters

##### properties?

[`IURLMetadata`](../interfaces/IURLMetadata.md)

Properties to set

#### Returns

[`URLMetadata`](URLMetadata.md)

## Properties

### fbExperimentId?

> `optional` **fbExperimentId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:35219](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35219)

URLMetadata fbExperimentId.

#### Implementation of

[`IURLMetadata`](../interfaces/IURLMetadata.md).[`fbExperimentId`](../interfaces/IURLMetadata.md#fbexperimentid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:35289](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35289)

Converts this URLMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:35226](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35226)

Creates a new URLMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IURLMetadata`](../interfaces/IURLMetadata.md)

Properties to set

#### Returns

[`URLMetadata`](URLMetadata.md)

URLMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:35252](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35252)

Decodes a URLMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`URLMetadata`](URLMetadata.md)

URLMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:35261](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35261)

Decodes a URLMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`URLMetadata`](URLMetadata.md)

URLMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35234](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35234)

Encodes the specified URLMetadata message. Does not implicitly [verify](URLMetadata.md#verify) messages.

#### Parameters

##### message

[`IURLMetadata`](../interfaces/IURLMetadata.md)

URLMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:35242](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35242)

Encodes the specified URLMetadata message, length delimited. Does not implicitly [verify](URLMetadata.md#verify) messages.

#### Parameters

##### message

[`IURLMetadata`](../interfaces/IURLMetadata.md)

URLMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:35275](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35275)

Creates a URLMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`URLMetadata`](URLMetadata.md)

URLMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:35296](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35296)

Gets the default type url for URLMetadata

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

Defined in: [WAProto/index.d.ts:35283](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35283)

Creates a plain object from a URLMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`URLMetadata`](URLMetadata.md)

URLMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:35268](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L35268)

Verifies a URLMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
