# Class: CallButton

Defined in: [WAProto/index.d.ts:50960](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50960)

Represents a CallButton.

## Implements

- [`ICallButton`](../interfaces/ICallButton.md)

## Constructors

### new CallButton()

> **new CallButton**(`properties`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:50966](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50966)

Constructs a new CallButton.

#### Parameters

##### properties?

[`ICallButton`](../interfaces/ICallButton.md)

Properties to set

#### Returns

[`CallButton`](CallButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:50969](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50969)

CallButton displayText.

#### Implementation of

[`ICallButton`](../interfaces/ICallButton.md).[`displayText`](../interfaces/ICallButton.md#displaytext)

***

### phoneNumber?

> `optional` **phoneNumber**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:50972](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50972)

CallButton phoneNumber.

#### Implementation of

[`ICallButton`](../interfaces/ICallButton.md).[`phoneNumber`](../interfaces/ICallButton.md#phonenumber)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51042](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L51042)

Converts this CallButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:50979](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50979)

Creates a new CallButton instance using the specified properties.

#### Parameters

##### properties?

[`ICallButton`](../interfaces/ICallButton.md)

Properties to set

#### Returns

[`CallButton`](CallButton.md)

CallButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:51005](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L51005)

Decodes a CallButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CallButton`](CallButton.md)

CallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:51014](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L51014)

Decodes a CallButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CallButton`](CallButton.md)

CallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50987](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50987)

Encodes the specified CallButton message. Does not implicitly [verify](CallButton.md#verify) messages.

#### Parameters

##### message

[`ICallButton`](../interfaces/ICallButton.md)

CallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50995](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L50995)

Encodes the specified CallButton message, length delimited. Does not implicitly [verify](CallButton.md#verify) messages.

#### Parameters

##### message

[`ICallButton`](../interfaces/ICallButton.md)

CallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:51028](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L51028)

Creates a CallButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CallButton`](CallButton.md)

CallButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51049](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L51049)

Gets the default type url for CallButton

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

Defined in: [WAProto/index.d.ts:51036](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L51036)

Creates a plain object from a CallButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`CallButton`](CallButton.md)

CallButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51021](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L51021)

Verifies a CallButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
