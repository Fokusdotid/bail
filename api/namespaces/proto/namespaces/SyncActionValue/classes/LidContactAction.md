# Class: LidContactAction

Defined in: [WAProto/index.d.ts:46069](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46069)

Represents a LidContactAction.

## Implements

- [`ILidContactAction`](../interfaces/ILidContactAction.md)

## Constructors

### new LidContactAction()

> **new LidContactAction**(`properties`?): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:46075](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46075)

Constructs a new LidContactAction.

#### Parameters

##### properties?

[`ILidContactAction`](../interfaces/ILidContactAction.md)

Properties to set

#### Returns

[`LidContactAction`](LidContactAction.md)

## Properties

### firstName?

> `optional` **firstName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46081](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46081)

LidContactAction firstName.

#### Implementation of

[`ILidContactAction`](../interfaces/ILidContactAction.md).[`firstName`](../interfaces/ILidContactAction.md#firstname)

***

### fullName?

> `optional` **fullName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46078](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46078)

LidContactAction fullName.

#### Implementation of

[`ILidContactAction`](../interfaces/ILidContactAction.md).[`fullName`](../interfaces/ILidContactAction.md#fullname)

***

### saveOnPrimaryAddressbook?

> `optional` **saveOnPrimaryAddressbook**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:46087](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46087)

LidContactAction saveOnPrimaryAddressbook.

#### Implementation of

[`ILidContactAction`](../interfaces/ILidContactAction.md).[`saveOnPrimaryAddressbook`](../interfaces/ILidContactAction.md#saveonprimaryaddressbook)

***

### username?

> `optional` **username**: `null` \| `string`

Defined in: [WAProto/index.d.ts:46084](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46084)

LidContactAction username.

#### Implementation of

[`ILidContactAction`](../interfaces/ILidContactAction.md).[`username`](../interfaces/ILidContactAction.md#username)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:46157](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46157)

Converts this LidContactAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:46094](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46094)

Creates a new LidContactAction instance using the specified properties.

#### Parameters

##### properties?

[`ILidContactAction`](../interfaces/ILidContactAction.md)

Properties to set

#### Returns

[`LidContactAction`](LidContactAction.md)

LidContactAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:46120](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46120)

Decodes a LidContactAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LidContactAction`](LidContactAction.md)

LidContactAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:46129](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46129)

Decodes a LidContactAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LidContactAction`](LidContactAction.md)

LidContactAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46102](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46102)

Encodes the specified LidContactAction message. Does not implicitly [verify](LidContactAction.md#verify) messages.

#### Parameters

##### message

[`ILidContactAction`](../interfaces/ILidContactAction.md)

LidContactAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:46110](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46110)

Encodes the specified LidContactAction message, length delimited. Does not implicitly [verify](LidContactAction.md#verify) messages.

#### Parameters

##### message

[`ILidContactAction`](../interfaces/ILidContactAction.md)

LidContactAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:46143](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46143)

Creates a LidContactAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LidContactAction`](LidContactAction.md)

LidContactAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:46164](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46164)

Gets the default type url for LidContactAction

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

Defined in: [WAProto/index.d.ts:46151](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46151)

Creates a plain object from a LidContactAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`LidContactAction`](LidContactAction.md)

LidContactAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:46136](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L46136)

Verifies a LidContactAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
