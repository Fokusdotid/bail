# Class: ReportingTokenInfo

Defined in: [WAProto/index.d.ts:40844](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40844)

Represents a ReportingTokenInfo.

## Implements

- [`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

## Constructors

### new ReportingTokenInfo()

> **new ReportingTokenInfo**(`properties`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:40850](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40850)

Constructs a new ReportingTokenInfo.

#### Parameters

##### properties?

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

Properties to set

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

## Properties

### reportingTag?

> `optional` **reportingTag**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:40853](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40853)

ReportingTokenInfo reportingTag.

#### Implementation of

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md).[`reportingTag`](../interfaces/IReportingTokenInfo.md#reportingtag)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:40923](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40923)

Converts this ReportingTokenInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:40860](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40860)

Creates a new ReportingTokenInfo instance using the specified properties.

#### Parameters

##### properties?

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

Properties to set

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:40886](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40886)

Decodes a ReportingTokenInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:40895](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40895)

Decodes a ReportingTokenInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40868](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40868)

Encodes the specified ReportingTokenInfo message. Does not implicitly [verify](ReportingTokenInfo.md#verify) messages.

#### Parameters

##### message

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

ReportingTokenInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40876](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40876)

Encodes the specified ReportingTokenInfo message, length delimited. Does not implicitly [verify](ReportingTokenInfo.md#verify) messages.

#### Parameters

##### message

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

ReportingTokenInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:40909](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40909)

Creates a ReportingTokenInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:40930](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40930)

Gets the default type url for ReportingTokenInfo

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

Defined in: [WAProto/index.d.ts:40917](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40917)

Creates a plain object from a ReportingTokenInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`ReportingTokenInfo`](ReportingTokenInfo.md)

ReportingTokenInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:40902](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L40902)

Verifies a ReportingTokenInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
