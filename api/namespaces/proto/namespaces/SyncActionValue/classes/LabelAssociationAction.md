# Class: LabelAssociationAction

Defined in: [WAProto/index.d.ts:45712](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45712)

Represents a LabelAssociationAction.

## Implements

- [`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

## Constructors

### new LabelAssociationAction()

> **new LabelAssociationAction**(`properties`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:45718](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45718)

Constructs a new LabelAssociationAction.

#### Parameters

##### properties?

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

Properties to set

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

## Properties

### labeled?

> `optional` **labeled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:45721](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45721)

LabelAssociationAction labeled.

#### Implementation of

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md).[`labeled`](../interfaces/ILabelAssociationAction.md#labeled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45791](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45791)

Converts this LabelAssociationAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:45728](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45728)

Creates a new LabelAssociationAction instance using the specified properties.

#### Parameters

##### properties?

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

Properties to set

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:45754](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45754)

Decodes a LabelAssociationAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:45763](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45763)

Decodes a LabelAssociationAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45736](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45736)

Encodes the specified LabelAssociationAction message. Does not implicitly [verify](LabelAssociationAction.md#verify) messages.

#### Parameters

##### message

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

LabelAssociationAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45744](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45744)

Encodes the specified LabelAssociationAction message, length delimited. Does not implicitly [verify](LabelAssociationAction.md#verify) messages.

#### Parameters

##### message

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

LabelAssociationAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:45777](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45777)

Creates a LabelAssociationAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45798](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45798)

Gets the default type url for LabelAssociationAction

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

Defined in: [WAProto/index.d.ts:45785](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45785)

Creates a plain object from a LabelAssociationAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`LabelAssociationAction`](LabelAssociationAction.md)

LabelAssociationAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:45770](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L45770)

Verifies a LabelAssociationAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
