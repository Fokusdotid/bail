# Class: KeepInChatMessage

Defined in: [WAProto/index.d.ts:26497](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26497)

Represents a KeepInChatMessage.

## Implements

- [`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

## Constructors

### new KeepInChatMessage()

> **new KeepInChatMessage**(`properties`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:26503](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26503)

Constructs a new KeepInChatMessage.

#### Parameters

##### properties?

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

Properties to set

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

## Properties

### keepType?

> `optional` **keepType**: `null` \| [`KeepType`](../../../enumerations/KeepType.md)

Defined in: [WAProto/index.d.ts:26509](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26509)

KeepInChatMessage keepType.

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`keepType`](../interfaces/IKeepInChatMessage.md#keeptype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:26506](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26506)

KeepInChatMessage key.

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`key`](../interfaces/IKeepInChatMessage.md#key)

***

### timestampMs?

> `optional` **timestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:26512](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26512)

KeepInChatMessage timestampMs.

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`timestampMs`](../interfaces/IKeepInChatMessage.md#timestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:26582](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26582)

Converts this KeepInChatMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:26519](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26519)

Creates a new KeepInChatMessage instance using the specified properties.

#### Parameters

##### properties?

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

Properties to set

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:26545](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26545)

Decodes a KeepInChatMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:26554](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26554)

Decodes a KeepInChatMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26527](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26527)

Encodes the specified KeepInChatMessage message. Does not implicitly [verify](KeepInChatMessage.md#verify) messages.

#### Parameters

##### message

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

KeepInChatMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:26535](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26535)

Encodes the specified KeepInChatMessage message, length delimited. Does not implicitly [verify](KeepInChatMessage.md#verify) messages.

#### Parameters

##### message

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

KeepInChatMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:26568](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26568)

Creates a KeepInChatMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:26589](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26589)

Gets the default type url for KeepInChatMessage

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

Defined in: [WAProto/index.d.ts:26576](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26576)

Creates a plain object from a KeepInChatMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`KeepInChatMessage`](KeepInChatMessage.md)

KeepInChatMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:26561](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L26561)

Verifies a KeepInChatMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
