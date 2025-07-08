# Class: Reportable

Defined in: [WAProto/index.d.ts:40738](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40738)

Represents a Reportable.

## Implements

- [`IReportable`](../interfaces/IReportable.md)

## Constructors

### new Reportable()

> **new Reportable**(`properties`?): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:40744](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40744)

Constructs a new Reportable.

#### Parameters

##### properties?

[`IReportable`](../interfaces/IReportable.md)

Properties to set

#### Returns

[`Reportable`](Reportable.md)

## Properties

### maxVersion?

> `optional` **maxVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:40750](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40750)

Reportable maxVersion.

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`maxVersion`](../interfaces/IReportable.md#maxversion)

***

### minVersion?

> `optional` **minVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:40747](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40747)

Reportable minVersion.

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`minVersion`](../interfaces/IReportable.md#minversion)

***

### never?

> `optional` **never**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:40756](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40756)

Reportable never.

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`never`](../interfaces/IReportable.md#never)

***

### notReportableMinVersion?

> `optional` **notReportableMinVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:40753](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40753)

Reportable notReportableMinVersion.

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`notReportableMinVersion`](../interfaces/IReportable.md#notreportableminversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:40826](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40826)

Converts this Reportable to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:40763](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40763)

Creates a new Reportable instance using the specified properties.

#### Parameters

##### properties?

[`IReportable`](../interfaces/IReportable.md)

Properties to set

#### Returns

[`Reportable`](Reportable.md)

Reportable instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:40789](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40789)

Decodes a Reportable message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Reportable`](Reportable.md)

Reportable

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:40798](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40798)

Decodes a Reportable message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Reportable`](Reportable.md)

Reportable

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40771](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40771)

Encodes the specified Reportable message. Does not implicitly [verify](Reportable.md#verify) messages.

#### Parameters

##### message

[`IReportable`](../interfaces/IReportable.md)

Reportable message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40779](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40779)

Encodes the specified Reportable message, length delimited. Does not implicitly [verify](Reportable.md#verify) messages.

#### Parameters

##### message

[`IReportable`](../interfaces/IReportable.md)

Reportable message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:40812](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40812)

Creates a Reportable message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Reportable`](Reportable.md)

Reportable

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:40833](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40833)

Gets the default type url for Reportable

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

Defined in: [WAProto/index.d.ts:40820](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40820)

Creates a plain object from a Reportable message. Also converts values to other types if specified.

#### Parameters

##### message

[`Reportable`](Reportable.md)

Reportable

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:40805](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L40805)

Verifies a Reportable message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
