# Class: StatusPrivacyAction

Defined in: [WAProto/index.d.ts:48677](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48677)

Represents a StatusPrivacyAction.

## Implements

- [`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

## Constructors

### new StatusPrivacyAction()

> **new StatusPrivacyAction**(`properties`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:48683](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48683)

Constructs a new StatusPrivacyAction.

#### Parameters

##### properties?

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

Properties to set

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

## Properties

### mode?

> `optional` **mode**: `null` \| [`StatusDistributionMode`](../namespaces/StatusPrivacyAction/enumerations/StatusDistributionMode.md)

Defined in: [WAProto/index.d.ts:48686](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48686)

StatusPrivacyAction mode.

#### Implementation of

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md).[`mode`](../interfaces/IStatusPrivacyAction.md#mode)

***

### userJid

> **userJid**: `string`[]

Defined in: [WAProto/index.d.ts:48689](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48689)

StatusPrivacyAction userJid.

#### Implementation of

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md).[`userJid`](../interfaces/IStatusPrivacyAction.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48759](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48759)

Converts this StatusPrivacyAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:48696](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48696)

Creates a new StatusPrivacyAction instance using the specified properties.

#### Parameters

##### properties?

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

Properties to set

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:48722](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48722)

Decodes a StatusPrivacyAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:48731](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48731)

Decodes a StatusPrivacyAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48704](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48704)

Encodes the specified StatusPrivacyAction message. Does not implicitly [verify](StatusPrivacyAction.md#verify) messages.

#### Parameters

##### message

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

StatusPrivacyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48712](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48712)

Encodes the specified StatusPrivacyAction message, length delimited. Does not implicitly [verify](StatusPrivacyAction.md#verify) messages.

#### Parameters

##### message

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

StatusPrivacyAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:48745](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48745)

Creates a StatusPrivacyAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48766](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48766)

Gets the default type url for StatusPrivacyAction

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

Defined in: [WAProto/index.d.ts:48753](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48753)

Creates a plain object from a StatusPrivacyAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`StatusPrivacyAction`](StatusPrivacyAction.md)

StatusPrivacyAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48738](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L48738)

Verifies a StatusPrivacyAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
