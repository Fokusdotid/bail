# Class: PollCreationMessage

Defined in: [WAProto/index.d.ts:31321](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31321)

Represents a PollCreationMessage.

## Implements

- [`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

## Constructors

### new PollCreationMessage()

> **new PollCreationMessage**(`properties`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:31327](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31327)

Constructs a new PollCreationMessage.

#### Parameters

##### properties?

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

Properties to set

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:31342](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31342)

PollCreationMessage contextInfo.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`contextInfo`](../interfaces/IPollCreationMessage.md#contextinfo)

***

### correctAnswer?

> `optional` **correctAnswer**: `null` \| [`IOption`](../namespaces/PollCreationMessage/interfaces/IOption.md)

Defined in: [WAProto/index.d.ts:31351](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31351)

PollCreationMessage correctAnswer.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`correctAnswer`](../interfaces/IPollCreationMessage.md#correctanswer)

***

### encKey?

> `optional` **encKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:31330](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31330)

PollCreationMessage encKey.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`encKey`](../interfaces/IPollCreationMessage.md#enckey)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:31333](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31333)

PollCreationMessage name.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`name`](../interfaces/IPollCreationMessage.md#name)

***

### options

> **options**: [`IOption`](../namespaces/PollCreationMessage/interfaces/IOption.md)[]

Defined in: [WAProto/index.d.ts:31336](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31336)

PollCreationMessage options.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`options`](../interfaces/IPollCreationMessage.md#options)

***

### pollContentType?

> `optional` **pollContentType**: `null` \| [`PollContentType`](../enumerations/PollContentType.md)

Defined in: [WAProto/index.d.ts:31345](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31345)

PollCreationMessage pollContentType.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`pollContentType`](../interfaces/IPollCreationMessage.md#pollcontenttype)

***

### pollType?

> `optional` **pollType**: `null` \| [`PollType`](../namespaces/PollCreationMessage/enumerations/PollType.md)

Defined in: [WAProto/index.d.ts:31348](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31348)

PollCreationMessage pollType.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`pollType`](../interfaces/IPollCreationMessage.md#polltype)

***

### selectableOptionsCount?

> `optional` **selectableOptionsCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:31339](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31339)

PollCreationMessage selectableOptionsCount.

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`selectableOptionsCount`](../interfaces/IPollCreationMessage.md#selectableoptionscount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31421](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31421)

Converts this PollCreationMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:31358](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31358)

Creates a new PollCreationMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

Properties to set

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:31384](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31384)

Decodes a PollCreationMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:31393](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31393)

Decodes a PollCreationMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31366](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31366)

Encodes the specified PollCreationMessage message. Does not implicitly [verify](PollCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

PollCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:31374](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31374)

Encodes the specified PollCreationMessage message, length delimited. Does not implicitly [verify](PollCreationMessage.md#verify) messages.

#### Parameters

##### message

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

PollCreationMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:31407](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31407)

Creates a PollCreationMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:31428](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31428)

Gets the default type url for PollCreationMessage

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

Defined in: [WAProto/index.d.ts:31415](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31415)

Creates a plain object from a PollCreationMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PollCreationMessage`](PollCreationMessage.md)

PollCreationMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31400](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L31400)

Verifies a PollCreationMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
