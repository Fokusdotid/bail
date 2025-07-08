# Class: BotLinkedAccountsMetadata

Defined in: [WAProto/index.d.ts:4216](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4216)

Represents a BotLinkedAccountsMetadata.

## Implements

- [`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

## Constructors

### new BotLinkedAccountsMetadata()

> **new BotLinkedAccountsMetadata**(`properties`?): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:4222](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4222)

Constructs a new BotLinkedAccountsMetadata.

#### Parameters

##### properties?

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

Properties to set

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

## Properties

### acAuthTokens?

> `optional` **acAuthTokens**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4228](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4228)

BotLinkedAccountsMetadata acAuthTokens.

#### Implementation of

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md).[`acAuthTokens`](../interfaces/IBotLinkedAccountsMetadata.md#acauthtokens)

***

### accounts

> **accounts**: [`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)[]

Defined in: [WAProto/index.d.ts:4225](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4225)

BotLinkedAccountsMetadata accounts.

#### Implementation of

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md).[`accounts`](../interfaces/IBotLinkedAccountsMetadata.md#accounts)

***

### acErrorCode?

> `optional` **acErrorCode**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4231](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4231)

BotLinkedAccountsMetadata acErrorCode.

#### Implementation of

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md).[`acErrorCode`](../interfaces/IBotLinkedAccountsMetadata.md#acerrorcode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4301](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4301)

Converts this BotLinkedAccountsMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:4238](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4238)

Creates a new BotLinkedAccountsMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

Properties to set

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

BotLinkedAccountsMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:4264](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4264)

Decodes a BotLinkedAccountsMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

BotLinkedAccountsMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:4273](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4273)

Decodes a BotLinkedAccountsMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

BotLinkedAccountsMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4246](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4246)

Encodes the specified BotLinkedAccountsMetadata message. Does not implicitly [verify](BotLinkedAccountsMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

BotLinkedAccountsMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:4254](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4254)

Encodes the specified BotLinkedAccountsMetadata message, length delimited. Does not implicitly [verify](BotLinkedAccountsMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

BotLinkedAccountsMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:4287](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4287)

Creates a BotLinkedAccountsMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

BotLinkedAccountsMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4308](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4308)

Gets the default type url for BotLinkedAccountsMetadata

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

Defined in: [WAProto/index.d.ts:4295](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4295)

Creates a plain object from a BotLinkedAccountsMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

BotLinkedAccountsMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:4280](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L4280)

Verifies a BotLinkedAccountsMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
