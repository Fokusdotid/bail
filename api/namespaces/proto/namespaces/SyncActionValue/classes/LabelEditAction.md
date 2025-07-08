# Class: LabelEditAction

Defined in: [WAProto/index.d.ts:45830](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45830)

Represents a LabelEditAction.

## Implements

- [`ILabelEditAction`](../interfaces/ILabelEditAction.md)

## Constructors

### new LabelEditAction()

> **new LabelEditAction**(`properties`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:45836](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45836)

Constructs a new LabelEditAction.

#### Parameters

##### properties?

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

Properties to set

#### Returns

[`LabelEditAction`](LabelEditAction.md)

## Properties

### color?

> `optional` **color**: `null` \| `number`

Defined in: [WAProto/index.d.ts:45842](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45842)

LabelEditAction color.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`color`](../interfaces/ILabelEditAction.md#color)

***

### deleted?

> `optional` **deleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:45848](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45848)

LabelEditAction deleted.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`deleted`](../interfaces/ILabelEditAction.md#deleted)

***

### isActive?

> `optional` **isActive**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:45854](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45854)

LabelEditAction isActive.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`isActive`](../interfaces/ILabelEditAction.md#isactive)

***

### isImmutable?

> `optional` **isImmutable**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:45860](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45860)

LabelEditAction isImmutable.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`isImmutable`](../interfaces/ILabelEditAction.md#isimmutable)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:45839](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45839)

LabelEditAction name.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`name`](../interfaces/ILabelEditAction.md#name)

***

### orderIndex?

> `optional` **orderIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:45851](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45851)

LabelEditAction orderIndex.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`orderIndex`](../interfaces/ILabelEditAction.md#orderindex)

***

### predefinedId?

> `optional` **predefinedId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:45845](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45845)

LabelEditAction predefinedId.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`predefinedId`](../interfaces/ILabelEditAction.md#predefinedid)

***

### type?

> `optional` **type**: `null` \| [`ListType`](../namespaces/LabelEditAction/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:45857](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45857)

LabelEditAction type.

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`type`](../interfaces/ILabelEditAction.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:45930](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45930)

Converts this LabelEditAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:45867](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45867)

Creates a new LabelEditAction instance using the specified properties.

#### Parameters

##### properties?

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

Properties to set

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:45893](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45893)

Decodes a LabelEditAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:45902](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45902)

Decodes a LabelEditAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45875](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45875)

Encodes the specified LabelEditAction message. Does not implicitly [verify](LabelEditAction.md#verify) messages.

#### Parameters

##### message

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

LabelEditAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:45883](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45883)

Encodes the specified LabelEditAction message, length delimited. Does not implicitly [verify](LabelEditAction.md#verify) messages.

#### Parameters

##### message

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

LabelEditAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:45916](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45916)

Creates a LabelEditAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:45937](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45937)

Gets the default type url for LabelEditAction

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

Defined in: [WAProto/index.d.ts:45924](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45924)

Creates a plain object from a LabelEditAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`LabelEditAction`](LabelEditAction.md)

LabelEditAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:45909](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L45909)

Verifies a LabelEditAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
