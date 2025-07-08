# Class: PrivacySettingDisableLinkPreviewsAction

Defined in: [WAProto/index.d.ts:47874](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47874)

Represents a PrivacySettingDisableLinkPreviewsAction.

## Implements

- [`IPrivacySettingDisableLinkPreviewsAction`](../interfaces/IPrivacySettingDisableLinkPreviewsAction.md)

## Constructors

### new PrivacySettingDisableLinkPreviewsAction()

> **new PrivacySettingDisableLinkPreviewsAction**(`properties`?): [`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

Defined in: [WAProto/index.d.ts:47880](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47880)

Constructs a new PrivacySettingDisableLinkPreviewsAction.

#### Parameters

##### properties?

[`IPrivacySettingDisableLinkPreviewsAction`](../interfaces/IPrivacySettingDisableLinkPreviewsAction.md)

Properties to set

#### Returns

[`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

## Properties

### isPreviewsDisabled?

> `optional` **isPreviewsDisabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:47883](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47883)

PrivacySettingDisableLinkPreviewsAction isPreviewsDisabled.

#### Implementation of

[`IPrivacySettingDisableLinkPreviewsAction`](../interfaces/IPrivacySettingDisableLinkPreviewsAction.md).[`isPreviewsDisabled`](../interfaces/IPrivacySettingDisableLinkPreviewsAction.md#ispreviewsdisabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:47953](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47953)

Converts this PrivacySettingDisableLinkPreviewsAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

Defined in: [WAProto/index.d.ts:47890](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47890)

Creates a new PrivacySettingDisableLinkPreviewsAction instance using the specified properties.

#### Parameters

##### properties?

[`IPrivacySettingDisableLinkPreviewsAction`](../interfaces/IPrivacySettingDisableLinkPreviewsAction.md)

Properties to set

#### Returns

[`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

PrivacySettingDisableLinkPreviewsAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

Defined in: [WAProto/index.d.ts:47916](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47916)

Decodes a PrivacySettingDisableLinkPreviewsAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

PrivacySettingDisableLinkPreviewsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

Defined in: [WAProto/index.d.ts:47925](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47925)

Decodes a PrivacySettingDisableLinkPreviewsAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

PrivacySettingDisableLinkPreviewsAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47898](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47898)

Encodes the specified PrivacySettingDisableLinkPreviewsAction message. Does not implicitly [verify](PrivacySettingDisableLinkPreviewsAction.md#verify) messages.

#### Parameters

##### message

[`IPrivacySettingDisableLinkPreviewsAction`](../interfaces/IPrivacySettingDisableLinkPreviewsAction.md)

PrivacySettingDisableLinkPreviewsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:47906](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47906)

Encodes the specified PrivacySettingDisableLinkPreviewsAction message, length delimited. Does not implicitly [verify](PrivacySettingDisableLinkPreviewsAction.md#verify) messages.

#### Parameters

##### message

[`IPrivacySettingDisableLinkPreviewsAction`](../interfaces/IPrivacySettingDisableLinkPreviewsAction.md)

PrivacySettingDisableLinkPreviewsAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

Defined in: [WAProto/index.d.ts:47939](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47939)

Creates a PrivacySettingDisableLinkPreviewsAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

PrivacySettingDisableLinkPreviewsAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:47960](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47960)

Gets the default type url for PrivacySettingDisableLinkPreviewsAction

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

Defined in: [WAProto/index.d.ts:47947](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47947)

Creates a plain object from a PrivacySettingDisableLinkPreviewsAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`PrivacySettingDisableLinkPreviewsAction`](PrivacySettingDisableLinkPreviewsAction.md)

PrivacySettingDisableLinkPreviewsAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:47932](https://github.com/Fokusdotid/bail/blob/c004679536d41fcf32da31cecf70d3991dfa31b5/WAProto/index.d.ts#L47932)

Verifies a PrivacySettingDisableLinkPreviewsAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
