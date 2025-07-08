# Class: CustomPaymentMethodMetadata

Defined in: [WAProto/index.d.ts:44821](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44821)

Represents a CustomPaymentMethodMetadata.

## Implements

- [`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

## Constructors

### new CustomPaymentMethodMetadata()

> **new CustomPaymentMethodMetadata**(`properties`?): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:44827](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44827)

Constructs a new CustomPaymentMethodMetadata.

#### Parameters

##### properties?

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

Properties to set

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

## Properties

### key

> **key**: `string`

Defined in: [WAProto/index.d.ts:44830](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44830)

CustomPaymentMethodMetadata key.

#### Implementation of

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md).[`key`](../interfaces/ICustomPaymentMethodMetadata.md#key)

***

### value

> **value**: `string`

Defined in: [WAProto/index.d.ts:44833](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44833)

CustomPaymentMethodMetadata value.

#### Implementation of

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md).[`value`](../interfaces/ICustomPaymentMethodMetadata.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:44903](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44903)

Converts this CustomPaymentMethodMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:44840](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44840)

Creates a new CustomPaymentMethodMetadata instance using the specified properties.

#### Parameters

##### properties?

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

Properties to set

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

CustomPaymentMethodMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:44866](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44866)

Decodes a CustomPaymentMethodMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

CustomPaymentMethodMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:44875](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44875)

Decodes a CustomPaymentMethodMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

CustomPaymentMethodMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44848](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44848)

Encodes the specified CustomPaymentMethodMetadata message. Does not implicitly [verify](CustomPaymentMethodMetadata.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

CustomPaymentMethodMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44856](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44856)

Encodes the specified CustomPaymentMethodMetadata message, length delimited. Does not implicitly [verify](CustomPaymentMethodMetadata.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

CustomPaymentMethodMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:44889](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44889)

Creates a CustomPaymentMethodMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

CustomPaymentMethodMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:44910](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44910)

Gets the default type url for CustomPaymentMethodMetadata

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

Defined in: [WAProto/index.d.ts:44897](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44897)

Creates a plain object from a CustomPaymentMethodMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

CustomPaymentMethodMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44882](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L44882)

Verifies a CustomPaymentMethodMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
