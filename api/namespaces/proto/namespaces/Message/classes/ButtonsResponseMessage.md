# Class: ButtonsResponseMessage

Defined in: [WAProto/index.d.ts:20760](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20760)

Represents a ButtonsResponseMessage.

## Implements

- [`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

## Constructors

### new ButtonsResponseMessage()

> **new ButtonsResponseMessage**(`properties`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:20766](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20766)

Constructs a new ButtonsResponseMessage.

#### Parameters

##### properties?

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

Properties to set

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:20772](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20772)

ButtonsResponseMessage contextInfo.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`contextInfo`](../interfaces/IButtonsResponseMessage.md#contextinfo)

***

### response?

> `optional` **response**: `"selectedDisplayText"`

Defined in: [WAProto/index.d.ts:20781](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20781)

ButtonsResponseMessage response.

***

### selectedButtonId?

> `optional` **selectedButtonId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20769](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20769)

ButtonsResponseMessage selectedButtonId.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`selectedButtonId`](../interfaces/IButtonsResponseMessage.md#selectedbuttonid)

***

### selectedDisplayText?

> `optional` **selectedDisplayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20778](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20778)

ButtonsResponseMessage selectedDisplayText.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`selectedDisplayText`](../interfaces/IButtonsResponseMessage.md#selecteddisplaytext)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/ButtonsResponseMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:20775](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20775)

ButtonsResponseMessage type.

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`type`](../interfaces/IButtonsResponseMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20851](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20851)

Converts this ButtonsResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:20788](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20788)

Creates a new ButtonsResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

Properties to set

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:20814](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20814)

Decodes a ButtonsResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:20823](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20823)

Decodes a ButtonsResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20796](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20796)

Encodes the specified ButtonsResponseMessage message. Does not implicitly [verify](ButtonsResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

ButtonsResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20804](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20804)

Encodes the specified ButtonsResponseMessage message, length delimited. Does not implicitly [verify](ButtonsResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

ButtonsResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:20837](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20837)

Creates a ButtonsResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:20858](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20858)

Gets the default type url for ButtonsResponseMessage

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

Defined in: [WAProto/index.d.ts:20845](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20845)

Creates a plain object from a ButtonsResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

ButtonsResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20830](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L20830)

Verifies a ButtonsResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
