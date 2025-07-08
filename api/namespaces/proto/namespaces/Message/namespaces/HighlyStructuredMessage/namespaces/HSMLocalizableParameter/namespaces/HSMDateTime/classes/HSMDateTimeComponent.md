# Class: HSMDateTimeComponent

Defined in: [WAProto/index.d.ts:24157](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24157)

Represents a HSMDateTimeComponent.

## Implements

- [`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

## Constructors

### new HSMDateTimeComponent()

> **new HSMDateTimeComponent**(`properties`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:24163](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24163)

Constructs a new HSMDateTimeComponent.

#### Parameters

##### properties?

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

Properties to set

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

## Properties

### calendar?

> `optional` **calendar**: `null` \| [`CalendarType`](../namespaces/HSMDateTimeComponent/enumerations/CalendarType.md)

Defined in: [WAProto/index.d.ts:24184](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24184)

HSMDateTimeComponent calendar.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`calendar`](../interfaces/IHSMDateTimeComponent.md#calendar)

***

### dayOfMonth?

> `optional` **dayOfMonth**: `null` \| `number`

Defined in: [WAProto/index.d.ts:24175](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24175)

HSMDateTimeComponent dayOfMonth.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`dayOfMonth`](../interfaces/IHSMDateTimeComponent.md#dayofmonth)

***

### dayOfWeek?

> `optional` **dayOfWeek**: `null` \| [`DayOfWeekType`](../namespaces/HSMDateTimeComponent/enumerations/DayOfWeekType.md)

Defined in: [WAProto/index.d.ts:24166](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24166)

HSMDateTimeComponent dayOfWeek.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`dayOfWeek`](../interfaces/IHSMDateTimeComponent.md#dayofweek)

***

### hour?

> `optional` **hour**: `null` \| `number`

Defined in: [WAProto/index.d.ts:24178](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24178)

HSMDateTimeComponent hour.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`hour`](../interfaces/IHSMDateTimeComponent.md#hour)

***

### minute?

> `optional` **minute**: `null` \| `number`

Defined in: [WAProto/index.d.ts:24181](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24181)

HSMDateTimeComponent minute.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`minute`](../interfaces/IHSMDateTimeComponent.md#minute)

***

### month?

> `optional` **month**: `null` \| `number`

Defined in: [WAProto/index.d.ts:24172](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24172)

HSMDateTimeComponent month.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`month`](../interfaces/IHSMDateTimeComponent.md#month)

***

### year?

> `optional` **year**: `null` \| `number`

Defined in: [WAProto/index.d.ts:24169](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24169)

HSMDateTimeComponent year.

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`year`](../interfaces/IHSMDateTimeComponent.md#year)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:24254](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24254)

Converts this HSMDateTimeComponent to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:24191](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24191)

Creates a new HSMDateTimeComponent instance using the specified properties.

#### Parameters

##### properties?

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

Properties to set

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:24217](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24217)

Decodes a HSMDateTimeComponent message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:24226](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24226)

Decodes a HSMDateTimeComponent message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24199](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24199)

Encodes the specified HSMDateTimeComponent message. Does not implicitly [verify](HSMDateTimeComponent.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

HSMDateTimeComponent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:24207](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24207)

Encodes the specified HSMDateTimeComponent message, length delimited. Does not implicitly [verify](HSMDateTimeComponent.md#verify) messages.

#### Parameters

##### message

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

HSMDateTimeComponent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:24240](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24240)

Creates a HSMDateTimeComponent message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:24261](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24261)

Gets the default type url for HSMDateTimeComponent

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

Defined in: [WAProto/index.d.ts:24248](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24248)

Creates a plain object from a HSMDateTimeComponent message. Also converts values to other types if specified.

#### Parameters

##### message

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

HSMDateTimeComponent

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:24233](https://github.com/Fokusdotid/bail/blob/c270ba4454f95d50cec87a9d90b03360fac7058e/WAProto/index.d.ts#L24233)

Verifies a HSMDateTimeComponent message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
