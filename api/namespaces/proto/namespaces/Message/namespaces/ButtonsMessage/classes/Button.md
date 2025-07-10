# Class: Button

Defined in: [WAProto/index.d.ts:20423](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20423)

Represents a Button.

## Implements

- [`IButton`](../interfaces/IButton.md)

## Constructors

### new Button()

> **new Button**(`properties`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:20429](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20429)

Constructs a new Button.

#### Parameters

##### properties?

[`IButton`](../interfaces/IButton.md)

Properties to set

#### Returns

[`Button`](Button.md)

## Properties

### buttonId?

> `optional` **buttonId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:20432](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20432)

Button buttonId.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`buttonId`](../interfaces/IButton.md#buttonid)

***

### buttonText?

> `optional` **buttonText**: `null` \| [`IButtonText`](../namespaces/Button/interfaces/IButtonText.md)

Defined in: [WAProto/index.d.ts:20435](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20435)

Button buttonText.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`buttonText`](../interfaces/IButton.md#buttontext)

***

### nativeFlowInfo?

> `optional` **nativeFlowInfo**: `null` \| [`INativeFlowInfo`](../namespaces/Button/interfaces/INativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:20441](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20441)

Button nativeFlowInfo.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`nativeFlowInfo`](../interfaces/IButton.md#nativeflowinfo)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/Button/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:20438](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20438)

Button type.

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`type`](../interfaces/IButton.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:20511](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20511)

Converts this Button to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:20448](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20448)

Creates a new Button instance using the specified properties.

#### Parameters

##### properties?

[`IButton`](../interfaces/IButton.md)

Properties to set

#### Returns

[`Button`](Button.md)

Button instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:20474](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20474)

Decodes a Button message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Button`](Button.md)

Button

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:20483](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20483)

Decodes a Button message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Button`](Button.md)

Button

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20456](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20456)

Encodes the specified Button message. Does not implicitly [verify](Button.md#verify) messages.

#### Parameters

##### message

[`IButton`](../interfaces/IButton.md)

Button message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:20464](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20464)

Encodes the specified Button message, length delimited. Does not implicitly [verify](Button.md#verify) messages.

#### Parameters

##### message

[`IButton`](../interfaces/IButton.md)

Button message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:20497](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20497)

Creates a Button message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Button`](Button.md)

Button

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:20518](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20518)

Gets the default type url for Button

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

Defined in: [WAProto/index.d.ts:20505](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20505)

Creates a plain object from a Button message. Also converts values to other types if specified.

#### Parameters

##### message

[`Button`](Button.md)

Button

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:20490](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L20490)

Verifies a Button message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
