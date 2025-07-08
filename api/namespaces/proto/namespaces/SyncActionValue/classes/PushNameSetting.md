# Class: PushNameSetting

Defined in: [WAProto/index.d.ts:48068](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48068)

Represents a PushNameSetting.

## Implements

- [`IPushNameSetting`](../interfaces/IPushNameSetting.md)

## Constructors

### new PushNameSetting()

> **new PushNameSetting**(`properties`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:48074](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48074)

Constructs a new PushNameSetting.

#### Parameters

##### properties?

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

Properties to set

#### Returns

[`PushNameSetting`](PushNameSetting.md)

## Properties

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:48077](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48077)

PushNameSetting name.

#### Implementation of

[`IPushNameSetting`](../interfaces/IPushNameSetting.md).[`name`](../interfaces/IPushNameSetting.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48147](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48147)

Converts this PushNameSetting to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:48084](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48084)

Creates a new PushNameSetting instance using the specified properties.

#### Parameters

##### properties?

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

Properties to set

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:48110](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48110)

Decodes a PushNameSetting message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:48119](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48119)

Decodes a PushNameSetting message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48092](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48092)

Encodes the specified PushNameSetting message. Does not implicitly [verify](PushNameSetting.md#verify) messages.

#### Parameters

##### message

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

PushNameSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48100](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48100)

Encodes the specified PushNameSetting message, length delimited. Does not implicitly [verify](PushNameSetting.md#verify) messages.

#### Parameters

##### message

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

PushNameSetting message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:48133](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48133)

Creates a PushNameSetting message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48154](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48154)

Gets the default type url for PushNameSetting

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

Defined in: [WAProto/index.d.ts:48141](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48141)

Creates a plain object from a PushNameSetting message. Also converts values to other types if specified.

#### Parameters

##### message

[`PushNameSetting`](PushNameSetting.md)

PushNameSetting

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48126](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L48126)

Verifies a PushNameSetting message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
