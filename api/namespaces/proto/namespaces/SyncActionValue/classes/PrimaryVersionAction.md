# Class: PrimaryVersionAction

Defined in: [WAProto/index.d.ts:47777](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47777)

Represents a PrimaryVersionAction.

## Implements

- [`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

## Constructors

### new PrimaryVersionAction()

> **new PrimaryVersionAction**(`properties`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:47783](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47783)

Constructs a new PrimaryVersionAction.

#### Parameters

##### properties?

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

Properties to set

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

## Properties

### version?

> `optional` **version**: `null` \| `string`

Defined in: [WAProto/index.d.ts:47786](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47786)

PrimaryVersionAction version.

#### Implementation of

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md).[`version`](../interfaces/IPrimaryVersionAction.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:47856](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47856)

Converts this PrimaryVersionAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:47793](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47793)

Creates a new PrimaryVersionAction instance using the specified properties.

#### Parameters

##### properties?

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

Properties to set

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:47819](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47819)

Decodes a PrimaryVersionAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:47828](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47828)

Decodes a PrimaryVersionAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47801](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47801)

Encodes the specified PrimaryVersionAction message. Does not implicitly [verify](PrimaryVersionAction.md#verify) messages.

#### Parameters

##### message

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

PrimaryVersionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47809](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47809)

Encodes the specified PrimaryVersionAction message, length delimited. Does not implicitly [verify](PrimaryVersionAction.md#verify) messages.

#### Parameters

##### message

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

PrimaryVersionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:47842](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47842)

Creates a PrimaryVersionAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:47863](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47863)

Gets the default type url for PrimaryVersionAction

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

Defined in: [WAProto/index.d.ts:47850](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47850)

Creates a plain object from a PrimaryVersionAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrimaryVersionAction`](PrimaryVersionAction.md)

PrimaryVersionAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:47835](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L47835)

Verifies a PrimaryVersionAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
