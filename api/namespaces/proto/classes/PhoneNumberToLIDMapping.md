# Class: PhoneNumberToLIDMapping

Defined in: [WAProto/index.d.ts:38827](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38827)

Represents a PhoneNumberToLIDMapping.

## Implements

- [`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

## Constructors

### new PhoneNumberToLIDMapping()

> **new PhoneNumberToLIDMapping**(`properties`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:38833](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38833)

Constructs a new PhoneNumberToLIDMapping.

#### Parameters

##### properties?

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

Properties to set

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

## Properties

### lidJid?

> `optional` **lidJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:38839](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38839)

PhoneNumberToLIDMapping lidJid.

#### Implementation of

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md).[`lidJid`](../interfaces/IPhoneNumberToLIDMapping.md#lidjid)

***

### pnJid?

> `optional` **pnJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:38836](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38836)

PhoneNumberToLIDMapping pnJid.

#### Implementation of

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md).[`pnJid`](../interfaces/IPhoneNumberToLIDMapping.md#pnjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:38909](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38909)

Converts this PhoneNumberToLIDMapping to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:38846](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38846)

Creates a new PhoneNumberToLIDMapping instance using the specified properties.

#### Parameters

##### properties?

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

Properties to set

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:38872](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38872)

Decodes a PhoneNumberToLIDMapping message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:38881](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38881)

Decodes a PhoneNumberToLIDMapping message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38854](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38854)

Encodes the specified PhoneNumberToLIDMapping message. Does not implicitly [verify](PhoneNumberToLIDMapping.md#verify) messages.

#### Parameters

##### message

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38862](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38862)

Encodes the specified PhoneNumberToLIDMapping message, length delimited. Does not implicitly [verify](PhoneNumberToLIDMapping.md#verify) messages.

#### Parameters

##### message

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:38895](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38895)

Creates a PhoneNumberToLIDMapping message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:38916](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38916)

Gets the default type url for PhoneNumberToLIDMapping

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

Defined in: [WAProto/index.d.ts:38903](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38903)

Creates a plain object from a PhoneNumberToLIDMapping message. Also converts values to other types if specified.

#### Parameters

##### message

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

PhoneNumberToLIDMapping

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:38888](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L38888)

Verifies a PhoneNumberToLIDMapping message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
