# Class: HydratedCallButton

Defined in: [WAProto/index.d.ts:16209](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16209)

Represents a HydratedCallButton.

## Implements

- [`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

## Constructors

### new HydratedCallButton()

> **new HydratedCallButton**(`properties`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:16215](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16215)

Constructs a new HydratedCallButton.

#### Parameters

##### properties?

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

Properties to set

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16218](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16218)

HydratedCallButton displayText.

#### Implementation of

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md).[`displayText`](../interfaces/IHydratedCallButton.md#displaytext)

***

### phoneNumber?

> `optional` **phoneNumber**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16221](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16221)

HydratedCallButton phoneNumber.

#### Implementation of

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md).[`phoneNumber`](../interfaces/IHydratedCallButton.md#phonenumber)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16291](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16291)

Converts this HydratedCallButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:16228](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16228)

Creates a new HydratedCallButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

Properties to set

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:16254](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16254)

Decodes a HydratedCallButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:16263](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16263)

Decodes a HydratedCallButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16236](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16236)

Encodes the specified HydratedCallButton message. Does not implicitly [verify](HydratedCallButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

HydratedCallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16244](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16244)

Encodes the specified HydratedCallButton message, length delimited. Does not implicitly [verify](HydratedCallButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

HydratedCallButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:16277](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16277)

Creates a HydratedCallButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:16298](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16298)

Gets the default type url for HydratedCallButton

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

Defined in: [WAProto/index.d.ts:16285](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16285)

Creates a plain object from a HydratedCallButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedCallButton`](HydratedCallButton.md)

HydratedCallButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16270](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16270)

Verifies a HydratedCallButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
