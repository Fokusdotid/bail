# Class: PhotoChange

Defined in: [WAProto/index.d.ts:38933](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38933)

Represents a PhotoChange.

## Implements

- [`IPhotoChange`](../interfaces/IPhotoChange.md)

## Constructors

### new PhotoChange()

> **new PhotoChange**(`properties`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:38939](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38939)

Constructs a new PhotoChange.

#### Parameters

##### properties?

[`IPhotoChange`](../interfaces/IPhotoChange.md)

Properties to set

#### Returns

[`PhotoChange`](PhotoChange.md)

## Properties

### newPhoto?

> `optional` **newPhoto**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:38945](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38945)

PhotoChange newPhoto.

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`newPhoto`](../interfaces/IPhotoChange.md#newphoto)

***

### newPhotoId?

> `optional` **newPhotoId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:38948](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38948)

PhotoChange newPhotoId.

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`newPhotoId`](../interfaces/IPhotoChange.md#newphotoid)

***

### oldPhoto?

> `optional` **oldPhoto**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:38942](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38942)

PhotoChange oldPhoto.

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`oldPhoto`](../interfaces/IPhotoChange.md#oldphoto)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:39018](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39018)

Converts this PhotoChange to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:38955](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38955)

Creates a new PhotoChange instance using the specified properties.

#### Parameters

##### properties?

[`IPhotoChange`](../interfaces/IPhotoChange.md)

Properties to set

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:38981](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38981)

Decodes a PhotoChange message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:38990](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38990)

Decodes a PhotoChange message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38963](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38963)

Encodes the specified PhotoChange message. Does not implicitly [verify](PhotoChange.md#verify) messages.

#### Parameters

##### message

[`IPhotoChange`](../interfaces/IPhotoChange.md)

PhotoChange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38971](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38971)

Encodes the specified PhotoChange message, length delimited. Does not implicitly [verify](PhotoChange.md#verify) messages.

#### Parameters

##### message

[`IPhotoChange`](../interfaces/IPhotoChange.md)

PhotoChange message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:39004](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39004)

Creates a PhotoChange message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PhotoChange`](PhotoChange.md)

PhotoChange

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:39025](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39025)

Gets the default type url for PhotoChange

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

Defined in: [WAProto/index.d.ts:39012](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L39012)

Creates a plain object from a PhotoChange message. Also converts values to other types if specified.

#### Parameters

##### message

[`PhotoChange`](PhotoChange.md)

PhotoChange

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:38997](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L38997)

Verifies a PhotoChange message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
