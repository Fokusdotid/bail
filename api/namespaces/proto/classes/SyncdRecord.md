# Class: SyncdRecord

Defined in: [WAProto/index.d.ts:50322](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50322)

Represents a SyncdRecord.

## Implements

- [`ISyncdRecord`](../interfaces/ISyncdRecord.md)

## Constructors

### new SyncdRecord()

> **new SyncdRecord**(`properties`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:50328](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50328)

Constructs a new SyncdRecord.

#### Parameters

##### properties?

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

Properties to set

#### Returns

[`SyncdRecord`](SyncdRecord.md)

## Properties

### index?

> `optional` **index**: `null` \| [`ISyncdIndex`](../interfaces/ISyncdIndex.md)

Defined in: [WAProto/index.d.ts:50331](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50331)

SyncdRecord index.

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`index`](../interfaces/ISyncdRecord.md#index)

***

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:50337](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50337)

SyncdRecord keyId.

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`keyId`](../interfaces/ISyncdRecord.md#keyid)

***

### value?

> `optional` **value**: `null` \| [`ISyncdValue`](../interfaces/ISyncdValue.md)

Defined in: [WAProto/index.d.ts:50334](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50334)

SyncdRecord value.

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`value`](../interfaces/ISyncdRecord.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50407](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50407)

Converts this SyncdRecord to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:50344](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50344)

Creates a new SyncdRecord instance using the specified properties.

#### Parameters

##### properties?

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

Properties to set

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:50370](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50370)

Decodes a SyncdRecord message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:50379](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50379)

Decodes a SyncdRecord message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50352](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50352)

Encodes the specified SyncdRecord message. Does not implicitly [verify](SyncdRecord.md#verify) messages.

#### Parameters

##### message

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

SyncdRecord message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50360](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50360)

Encodes the specified SyncdRecord message, length delimited. Does not implicitly [verify](SyncdRecord.md#verify) messages.

#### Parameters

##### message

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

SyncdRecord message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:50393](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50393)

Creates a SyncdRecord message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50414](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50414)

Gets the default type url for SyncdRecord

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

Defined in: [WAProto/index.d.ts:50401](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50401)

Creates a plain object from a SyncdRecord message. Also converts values to other types if specified.

#### Parameters

##### message

[`SyncdRecord`](SyncdRecord.md)

SyncdRecord

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50386](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50386)

Verifies a SyncdRecord message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
