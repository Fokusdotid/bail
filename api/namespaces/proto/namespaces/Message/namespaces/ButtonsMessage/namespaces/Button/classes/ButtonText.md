# Class: ButtonText

Defined in: [WAProto/index.d.ts:20531](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20531)

Represents a ButtonText.

## Implements

- [`IButtonText`](../interfaces/IButtonText.md)

## Constructors

### new ButtonText()

> **new ButtonText**(`properties`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:20537](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20537)

Constructs a new ButtonText.

#### Parameters

##### properties?

[`IButtonText`](../interfaces/IButtonText.md)

Properties to set

#### Returns

[`ButtonText`](ButtonText.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20540](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20540)

ButtonText displayText.

#### Implementation of

[`IButtonText`](../interfaces/IButtonText.md).[`displayText`](../interfaces/IButtonText.md#displaytext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20610](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20610)

Converts this ButtonText to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:20547](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20547)

Creates a new ButtonText instance using the specified properties.

#### Parameters

##### properties?

[`IButtonText`](../interfaces/IButtonText.md)

Properties to set

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:20573](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20573)

Decodes a ButtonText message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:20582](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20582)

Decodes a ButtonText message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20555](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20555)

Encodes the specified ButtonText message. Does not implicitly [verify](ButtonText.md#verify) messages.

#### Parameters

##### message

[`IButtonText`](../interfaces/IButtonText.md)

ButtonText message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20563](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20563)

Encodes the specified ButtonText message, length delimited. Does not implicitly [verify](ButtonText.md#verify) messages.

#### Parameters

##### message

[`IButtonText`](../interfaces/IButtonText.md)

ButtonText message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:20596](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20596)

Creates a ButtonText message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ButtonText`](ButtonText.md)

ButtonText

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:20617](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20617)

Gets the default type url for ButtonText

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

Defined in: [WAProto/index.d.ts:20604](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20604)

Creates a plain object from a ButtonText message. Also converts values to other types if specified.

#### Parameters

##### message

[`ButtonText`](ButtonText.md)

ButtonText

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20589](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L20589)

Verifies a ButtonText message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
