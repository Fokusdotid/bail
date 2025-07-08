# Class: HSMLocalizableParameter

Defined in: [WAProto/index.d.ts:23820](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23820)

Represents a HSMLocalizableParameter.

## Implements

- [`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

## Constructors

### new HSMLocalizableParameter()

> **new HSMLocalizableParameter**(`properties`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:23826](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23826)

Constructs a new HSMLocalizableParameter.

#### Parameters

##### properties?

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

Properties to set

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

## Properties

### currency?

> `optional` **currency**: `null` \| [`IHSMCurrency`](../namespaces/HSMLocalizableParameter/interfaces/IHSMCurrency.md)

Defined in: [WAProto/index.d.ts:23832](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23832)

HSMLocalizableParameter currency.

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`currency`](../interfaces/IHSMLocalizableParameter.md#currency)

***

### dateTime?

> `optional` **dateTime**: `null` \| [`IHSMDateTime`](../namespaces/HSMLocalizableParameter/interfaces/IHSMDateTime.md)

Defined in: [WAProto/index.d.ts:23835](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23835)

HSMLocalizableParameter dateTime.

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`dateTime`](../interfaces/IHSMLocalizableParameter.md#datetime)

***

### default?

> `optional` **default**: `null` \| `string`

Defined in: [WAProto/index.d.ts:23829](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23829)

HSMLocalizableParameter default.

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`default`](../interfaces/IHSMLocalizableParameter.md#default)

***

### paramOneof?

> `optional` **paramOneof**: `"currency"` \| `"dateTime"`

Defined in: [WAProto/index.d.ts:23838](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23838)

HSMLocalizableParameter paramOneof.

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:23908](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23908)

Converts this HSMLocalizableParameter to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:23845](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23845)

Creates a new HSMLocalizableParameter instance using the specified properties.

#### Parameters

##### properties?

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

Properties to set

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:23871](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23871)

Decodes a HSMLocalizableParameter message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:23880](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23880)

Decodes a HSMLocalizableParameter message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23853](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23853)

Encodes the specified HSMLocalizableParameter message. Does not implicitly [verify](HSMLocalizableParameter.md#verify) messages.

#### Parameters

##### message

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

HSMLocalizableParameter message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:23861](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23861)

Encodes the specified HSMLocalizableParameter message, length delimited. Does not implicitly [verify](HSMLocalizableParameter.md#verify) messages.

#### Parameters

##### message

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

HSMLocalizableParameter message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:23894](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23894)

Creates a HSMLocalizableParameter message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:23915](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23915)

Gets the default type url for HSMLocalizableParameter

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

Defined in: [WAProto/index.d.ts:23902](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23902)

Creates a plain object from a HSMLocalizableParameter message. Also converts values to other types if specified.

#### Parameters

##### message

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

HSMLocalizableParameter

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:23887](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L23887)

Verifies a HSMLocalizableParameter message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
