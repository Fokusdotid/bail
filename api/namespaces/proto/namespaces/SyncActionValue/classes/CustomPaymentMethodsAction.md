# Class: CustomPaymentMethodsAction

Defined in: [WAProto/index.d.ts:44921](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44921)

Represents a CustomPaymentMethodsAction.

## Implements

- [`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

## Constructors

### new CustomPaymentMethodsAction()

> **new CustomPaymentMethodsAction**(`properties`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:44927](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44927)

Constructs a new CustomPaymentMethodsAction.

#### Parameters

##### properties?

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

Properties to set

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

## Properties

### customPaymentMethods

> **customPaymentMethods**: [`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)[]

Defined in: [WAProto/index.d.ts:44930](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44930)

CustomPaymentMethodsAction customPaymentMethods.

#### Implementation of

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md).[`customPaymentMethods`](../interfaces/ICustomPaymentMethodsAction.md#custompaymentmethods)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45000](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45000)

Converts this CustomPaymentMethodsAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:44937](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44937)

Creates a new CustomPaymentMethodsAction instance using the specified properties.

#### Parameters

##### properties?

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

Properties to set

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:44963](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44963)

Decodes a CustomPaymentMethodsAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:44972](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44972)

Decodes a CustomPaymentMethodsAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44945](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44945)

Encodes the specified CustomPaymentMethodsAction message. Does not implicitly [verify](CustomPaymentMethodsAction.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

CustomPaymentMethodsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:44953](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44953)

Encodes the specified CustomPaymentMethodsAction message, length delimited. Does not implicitly [verify](CustomPaymentMethodsAction.md#verify) messages.

#### Parameters

##### message

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

CustomPaymentMethodsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:44986](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44986)

Creates a CustomPaymentMethodsAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45007](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L45007)

Gets the default type url for CustomPaymentMethodsAction

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

Defined in: [WAProto/index.d.ts:44994](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44994)

Creates a plain object from a CustomPaymentMethodsAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

CustomPaymentMethodsAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:44979](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L44979)

Verifies a CustomPaymentMethodsAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
