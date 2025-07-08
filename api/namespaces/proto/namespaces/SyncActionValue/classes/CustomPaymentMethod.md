# Class: CustomPaymentMethod

Defined in: [WAProto/index.d.ts:44712](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44712)

Represents a CustomPaymentMethod.

## Implements

- [`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

## Constructors

### new CustomPaymentMethod()

> **new CustomPaymentMethod**(`properties`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:44718](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44718)

Constructs a new CustomPaymentMethod.

#### Parameters

##### properties?

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

Properties to set

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

## Properties

### country

> **country**: `string`

Defined in: [WAProto/index.d.ts:44724](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44724)

CustomPaymentMethod country.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`country`](../interfaces/ICustomPaymentMethod.md#country)

***

### credentialId

> **credentialId**: `string`

Defined in: [WAProto/index.d.ts:44721](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44721)

CustomPaymentMethod credentialId.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`credentialId`](../interfaces/ICustomPaymentMethod.md#credentialid)

***

### metadata

> **metadata**: [`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)[]

Defined in: [WAProto/index.d.ts:44730](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44730)

CustomPaymentMethod metadata.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`metadata`](../interfaces/ICustomPaymentMethod.md#metadata)

***

### type

> **type**: `string`

Defined in: [WAProto/index.d.ts:44727](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44727)

CustomPaymentMethod type.

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`type`](../interfaces/ICustomPaymentMethod.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:44800](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44800)

Converts this CustomPaymentMethod to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:44737](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44737)

Creates a new CustomPaymentMethod instance using the specified properties.

#### Parameters

##### properties?

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

Properties to set

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:44763](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44763)

Decodes a CustomPaymentMethod message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:44772](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44772)

Decodes a CustomPaymentMethod message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44745](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44745)

Encodes the specified CustomPaymentMethod message. Does not implicitly [verify](CustomPaymentMethod.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

CustomPaymentMethod message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44753](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44753)

Encodes the specified CustomPaymentMethod message, length delimited. Does not implicitly [verify](CustomPaymentMethod.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

CustomPaymentMethod message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:44786](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44786)

Creates a CustomPaymentMethod message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:44807](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44807)

Gets the default type url for CustomPaymentMethod

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

Defined in: [WAProto/index.d.ts:44794](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44794)

Creates a plain object from a CustomPaymentMethod message. Also converts values to other types if specified.

#### Parameters

##### message

[`CustomPaymentMethod`](CustomPaymentMethod.md)

CustomPaymentMethod

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44779](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L44779)

Verifies a CustomPaymentMethod message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
