# Class: ContactsArrayMessage

Defined in: [WAProto/index.d.ts:21909](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21909)

Represents a ContactsArrayMessage.

## Implements

- [`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

## Constructors

### new ContactsArrayMessage()

> **new ContactsArrayMessage**(`properties`?): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:21915](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21915)

Constructs a new ContactsArrayMessage.

#### Parameters

##### properties?

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

Properties to set

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

## Properties

### contacts

> **contacts**: [`IContactMessage`](../interfaces/IContactMessage.md)[]

Defined in: [WAProto/index.d.ts:21921](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21921)

ContactsArrayMessage contacts.

#### Implementation of

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md).[`contacts`](../interfaces/IContactsArrayMessage.md#contacts)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:21924](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21924)

ContactsArrayMessage contextInfo.

#### Implementation of

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md).[`contextInfo`](../interfaces/IContactsArrayMessage.md#contextinfo)

***

### displayName?

> `optional` **displayName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21918](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21918)

ContactsArrayMessage displayName.

#### Implementation of

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md).[`displayName`](../interfaces/IContactsArrayMessage.md#displayname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21994](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21994)

Converts this ContactsArrayMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:21931](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21931)

Creates a new ContactsArrayMessage instance using the specified properties.

#### Parameters

##### properties?

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

Properties to set

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:21957](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21957)

Decodes a ContactsArrayMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:21966](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21966)

Decodes a ContactsArrayMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21939](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21939)

Encodes the specified ContactsArrayMessage message. Does not implicitly [verify](ContactsArrayMessage.md#verify) messages.

#### Parameters

##### message

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

ContactsArrayMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21947](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21947)

Encodes the specified ContactsArrayMessage message, length delimited. Does not implicitly [verify](ContactsArrayMessage.md#verify) messages.

#### Parameters

##### message

[`IContactsArrayMessage`](../interfaces/IContactsArrayMessage.md)

ContactsArrayMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ContactsArrayMessage`](ContactsArrayMessage.md)

Defined in: [WAProto/index.d.ts:21980](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21980)

Creates a ContactsArrayMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:22001](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L22001)

Gets the default type url for ContactsArrayMessage

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

Defined in: [WAProto/index.d.ts:21988](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21988)

Creates a plain object from a ContactsArrayMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ContactsArrayMessage`](ContactsArrayMessage.md)

ContactsArrayMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21973](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L21973)

Verifies a ContactsArrayMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
