# Class: ContactAction

Defined in: [WAProto/index.d.ts:44494](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44494)

Represents a ContactAction.

## Implements

- [`IContactAction`](../interfaces/IContactAction.md)

## Constructors

### new ContactAction()

> **new ContactAction**(`properties`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:44500](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44500)

Constructs a new ContactAction.

#### Parameters

##### properties?

[`IContactAction`](../interfaces/IContactAction.md)

Properties to set

#### Returns

[`ContactAction`](ContactAction.md)

## Properties

### firstName?

> `optional` **firstName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:44506](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44506)

ContactAction firstName.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`firstName`](../interfaces/IContactAction.md#firstname)

***

### fullName?

> `optional` **fullName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:44503](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44503)

ContactAction fullName.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`fullName`](../interfaces/IContactAction.md#fullname)

***

### lidJid?

> `optional` **lidJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:44509](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44509)

ContactAction lidJid.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`lidJid`](../interfaces/IContactAction.md#lidjid)

***

### pnJid?

> `optional` **pnJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:44515](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44515)

ContactAction pnJid.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`pnJid`](../interfaces/IContactAction.md#pnjid)

***

### saveOnPrimaryAddressbook?

> `optional` **saveOnPrimaryAddressbook**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:44512](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44512)

ContactAction saveOnPrimaryAddressbook.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`saveOnPrimaryAddressbook`](../interfaces/IContactAction.md#saveonprimaryaddressbook)

***

### username?

> `optional` **username**: `null` \| `string`

Defined in: [WAProto/index.d.ts:44518](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44518)

ContactAction username.

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`username`](../interfaces/IContactAction.md#username)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:44588](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44588)

Converts this ContactAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:44525](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44525)

Creates a new ContactAction instance using the specified properties.

#### Parameters

##### properties?

[`IContactAction`](../interfaces/IContactAction.md)

Properties to set

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:44551](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44551)

Decodes a ContactAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:44560](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44560)

Decodes a ContactAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44533](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44533)

Encodes the specified ContactAction message. Does not implicitly [verify](ContactAction.md#verify) messages.

#### Parameters

##### message

[`IContactAction`](../interfaces/IContactAction.md)

ContactAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44541](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44541)

Encodes the specified ContactAction message, length delimited. Does not implicitly [verify](ContactAction.md#verify) messages.

#### Parameters

##### message

[`IContactAction`](../interfaces/IContactAction.md)

ContactAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:44574](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44574)

Creates a ContactAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ContactAction`](ContactAction.md)

ContactAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:44595](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44595)

Gets the default type url for ContactAction

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

Defined in: [WAProto/index.d.ts:44582](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44582)

Creates a plain object from a ContactAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`ContactAction`](ContactAction.md)

ContactAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44567](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L44567)

Verifies a ContactAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
