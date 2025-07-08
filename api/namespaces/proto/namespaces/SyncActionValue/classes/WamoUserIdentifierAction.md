# Class: WamoUserIdentifierAction

Defined in: [WAProto/index.d.ts:49767](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49767)

Represents a WamoUserIdentifierAction.

## Implements

- [`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

## Constructors

### new WamoUserIdentifierAction()

> **new WamoUserIdentifierAction**(`properties`?): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:49773](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49773)

Constructs a new WamoUserIdentifierAction.

#### Parameters

##### properties?

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

Properties to set

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

## Properties

### identifier?

> `optional` **identifier**: `null` \| `string`

Defined in: [WAProto/index.d.ts:49776](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49776)

WamoUserIdentifierAction identifier.

#### Implementation of

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md).[`identifier`](../interfaces/IWamoUserIdentifierAction.md#identifier)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:49846](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49846)

Converts this WamoUserIdentifierAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:49783](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49783)

Creates a new WamoUserIdentifierAction instance using the specified properties.

#### Parameters

##### properties?

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

Properties to set

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

WamoUserIdentifierAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:49809](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49809)

Decodes a WamoUserIdentifierAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

WamoUserIdentifierAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:49818](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49818)

Decodes a WamoUserIdentifierAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

WamoUserIdentifierAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49791](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49791)

Encodes the specified WamoUserIdentifierAction message. Does not implicitly [verify](WamoUserIdentifierAction.md#verify) messages.

#### Parameters

##### message

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

WamoUserIdentifierAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:49799](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49799)

Encodes the specified WamoUserIdentifierAction message, length delimited. Does not implicitly [verify](WamoUserIdentifierAction.md#verify) messages.

#### Parameters

##### message

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

WamoUserIdentifierAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:49832](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49832)

Creates a WamoUserIdentifierAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

WamoUserIdentifierAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:49853](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49853)

Gets the default type url for WamoUserIdentifierAction

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

Defined in: [WAProto/index.d.ts:49840](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49840)

Creates a plain object from a WamoUserIdentifierAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

WamoUserIdentifierAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:49825](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L49825)

Verifies a WamoUserIdentifierAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
