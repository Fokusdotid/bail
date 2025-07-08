# Class: Account

Defined in: [WAProto/index.d.ts:2806](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2806)

Represents an Account.

## Implements

- [`IAccount`](../interfaces/IAccount.md)

## Constructors

### new Account()

> **new Account**(`properties`?): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:2812](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2812)

Constructs a new Account.

#### Parameters

##### properties?

[`IAccount`](../interfaces/IAccount.md)

Properties to set

#### Returns

[`Account`](Account.md)

## Properties

### countryCode?

> `optional` **countryCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2821](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2821)

Account countryCode.

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`countryCode`](../interfaces/IAccount.md#countrycode)

***

### isUsernameDeleted?

> `optional` **isUsernameDeleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2824](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2824)

Account isUsernameDeleted.

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`isUsernameDeleted`](../interfaces/IAccount.md#isusernamedeleted)

***

### lid?

> `optional` **lid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2815](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2815)

Account lid.

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`lid`](../interfaces/IAccount.md#lid)

***

### username?

> `optional` **username**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2818](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2818)

Account username.

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`username`](../interfaces/IAccount.md#username)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2894](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2894)

Converts this Account to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:2831](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2831)

Creates a new Account instance using the specified properties.

#### Parameters

##### properties?

[`IAccount`](../interfaces/IAccount.md)

Properties to set

#### Returns

[`Account`](Account.md)

Account instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:2857](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2857)

Decodes an Account message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Account`](Account.md)

Account

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:2866](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2866)

Decodes an Account message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Account`](Account.md)

Account

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2839](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2839)

Encodes the specified Account message. Does not implicitly [verify](Account.md#verify) messages.

#### Parameters

##### message

[`IAccount`](../interfaces/IAccount.md)

Account message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2847](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2847)

Encodes the specified Account message, length delimited. Does not implicitly [verify](Account.md#verify) messages.

#### Parameters

##### message

[`IAccount`](../interfaces/IAccount.md)

Account message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:2880](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2880)

Creates an Account message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Account`](Account.md)

Account

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2901](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2901)

Gets the default type url for Account

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

Defined in: [WAProto/index.d.ts:2888](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2888)

Creates a plain object from an Account message. Also converts values to other types if specified.

#### Parameters

##### message

[`Account`](Account.md)

Account

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2873](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L2873)

Verifies an Account message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
