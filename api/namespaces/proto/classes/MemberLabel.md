# Class: MemberLabel

Defined in: [WAProto/index.d.ts:18243](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18243)

Represents a MemberLabel.

## Implements

- [`IMemberLabel`](../interfaces/IMemberLabel.md)

## Constructors

### new MemberLabel()

> **new MemberLabel**(`properties`?): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:18249](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18249)

Constructs a new MemberLabel.

#### Parameters

##### properties?

[`IMemberLabel`](../interfaces/IMemberLabel.md)

Properties to set

#### Returns

[`MemberLabel`](MemberLabel.md)

## Properties

### label?

> `optional` **label**: `null` \| `string`

Defined in: [WAProto/index.d.ts:18252](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18252)

MemberLabel label.

#### Implementation of

[`IMemberLabel`](../interfaces/IMemberLabel.md).[`label`](../interfaces/IMemberLabel.md#label)

***

### labelTimestamp?

> `optional` **labelTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:18255](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18255)

MemberLabel labelTimestamp.

#### Implementation of

[`IMemberLabel`](../interfaces/IMemberLabel.md).[`labelTimestamp`](../interfaces/IMemberLabel.md#labeltimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:18325](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18325)

Converts this MemberLabel to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:18262](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18262)

Creates a new MemberLabel instance using the specified properties.

#### Parameters

##### properties?

[`IMemberLabel`](../interfaces/IMemberLabel.md)

Properties to set

#### Returns

[`MemberLabel`](MemberLabel.md)

MemberLabel instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:18288](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18288)

Decodes a MemberLabel message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`MemberLabel`](MemberLabel.md)

MemberLabel

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:18297](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18297)

Decodes a MemberLabel message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`MemberLabel`](MemberLabel.md)

MemberLabel

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18270](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18270)

Encodes the specified MemberLabel message. Does not implicitly [verify](MemberLabel.md#verify) messages.

#### Parameters

##### message

[`IMemberLabel`](../interfaces/IMemberLabel.md)

MemberLabel message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:18278](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18278)

Encodes the specified MemberLabel message, length delimited. Does not implicitly [verify](MemberLabel.md#verify) messages.

#### Parameters

##### message

[`IMemberLabel`](../interfaces/IMemberLabel.md)

MemberLabel message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:18311](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18311)

Creates a MemberLabel message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`MemberLabel`](MemberLabel.md)

MemberLabel

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:18332](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18332)

Gets the default type url for MemberLabel

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

Defined in: [WAProto/index.d.ts:18319](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18319)

Creates a plain object from a MemberLabel message. Also converts values to other types if specified.

#### Parameters

##### message

[`MemberLabel`](MemberLabel.md)

MemberLabel

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:18304](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L18304)

Verifies a MemberLabel message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
