# Class: SubscriptionAction

Defined in: [WAProto/index.d.ts:48950](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48950)

Represents a SubscriptionAction.

## Implements

- [`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

## Constructors

### new SubscriptionAction()

> **new SubscriptionAction**(`properties`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:48956](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48956)

Constructs a new SubscriptionAction.

#### Parameters

##### properties?

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

Properties to set

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

## Properties

### expirationDate?

> `optional` **expirationDate**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:48965](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48965)

SubscriptionAction expirationDate.

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`expirationDate`](../interfaces/ISubscriptionAction.md#expirationdate)

***

### isAutoRenewing?

> `optional` **isAutoRenewing**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:48962](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48962)

SubscriptionAction isAutoRenewing.

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`isAutoRenewing`](../interfaces/ISubscriptionAction.md#isautorenewing)

***

### isDeactivated?

> `optional` **isDeactivated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:48959](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48959)

SubscriptionAction isDeactivated.

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`isDeactivated`](../interfaces/ISubscriptionAction.md#isdeactivated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:49035](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L49035)

Converts this SubscriptionAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:48972](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48972)

Creates a new SubscriptionAction instance using the specified properties.

#### Parameters

##### properties?

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

Properties to set

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:48998](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48998)

Decodes a SubscriptionAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:49007](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L49007)

Decodes a SubscriptionAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48980](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48980)

Encodes the specified SubscriptionAction message. Does not implicitly [verify](SubscriptionAction.md#verify) messages.

#### Parameters

##### message

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

SubscriptionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48988](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L48988)

Encodes the specified SubscriptionAction message, length delimited. Does not implicitly [verify](SubscriptionAction.md#verify) messages.

#### Parameters

##### message

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

SubscriptionAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:49021](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L49021)

Creates a SubscriptionAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:49042](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L49042)

Gets the default type url for SubscriptionAction

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

Defined in: [WAProto/index.d.ts:49029](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L49029)

Creates a plain object from a SubscriptionAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`SubscriptionAction`](SubscriptionAction.md)

SubscriptionAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:49014](https://github.com/Fokusdotid/bail/blob/fcd0cec6f26de1fb545eb2e03fa5c63fbad99d3d/WAProto/index.d.ts#L49014)

Verifies a SubscriptionAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
