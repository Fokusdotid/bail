# Class: DisappearingMode

Defined in: [WAProto/index.d.ts:13648](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13648)

Represents a DisappearingMode.

## Implements

- [`IDisappearingMode`](../interfaces/IDisappearingMode.md)

## Constructors

### new DisappearingMode()

> **new DisappearingMode**(`properties`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:13654](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13654)

Constructs a new DisappearingMode.

#### Parameters

##### properties?

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

Properties to set

#### Returns

[`DisappearingMode`](DisappearingMode.md)

## Properties

### initiatedByMe?

> `optional` **initiatedByMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:13666](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13666)

DisappearingMode initiatedByMe.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiatedByMe`](../interfaces/IDisappearingMode.md#initiatedbyme)

***

### initiator?

> `optional` **initiator**: `null` \| [`Initiator`](../namespaces/DisappearingMode/enumerations/Initiator.md)

Defined in: [WAProto/index.d.ts:13657](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13657)

DisappearingMode initiator.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiator`](../interfaces/IDisappearingMode.md#initiator)

***

### initiatorDeviceJid?

> `optional` **initiatorDeviceJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13663](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13663)

DisappearingMode initiatorDeviceJid.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiatorDeviceJid`](../interfaces/IDisappearingMode.md#initiatordevicejid)

***

### trigger?

> `optional` **trigger**: `null` \| [`Trigger`](../namespaces/DisappearingMode/enumerations/Trigger.md)

Defined in: [WAProto/index.d.ts:13660](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13660)

DisappearingMode trigger.

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`trigger`](../interfaces/IDisappearingMode.md#trigger)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13736](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13736)

Converts this DisappearingMode to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:13673](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13673)

Creates a new DisappearingMode instance using the specified properties.

#### Parameters

##### properties?

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

Properties to set

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:13699](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13699)

Decodes a DisappearingMode message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:13708](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13708)

Decodes a DisappearingMode message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13681](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13681)

Encodes the specified DisappearingMode message. Does not implicitly [verify](DisappearingMode.md#verify) messages.

#### Parameters

##### message

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

DisappearingMode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13689](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13689)

Encodes the specified DisappearingMode message, length delimited. Does not implicitly [verify](DisappearingMode.md#verify) messages.

#### Parameters

##### message

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

DisappearingMode message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:13722](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13722)

Creates a DisappearingMode message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13743](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13743)

Gets the default type url for DisappearingMode

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

Defined in: [WAProto/index.d.ts:13730](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13730)

Creates a plain object from a DisappearingMode message. Also converts values to other types if specified.

#### Parameters

##### message

[`DisappearingMode`](DisappearingMode.md)

DisappearingMode

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13715](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L13715)

Verifies a DisappearingMode message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
