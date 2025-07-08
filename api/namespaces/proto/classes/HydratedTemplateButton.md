# Class: HydratedTemplateButton

Defined in: [WAProto/index.d.ts:16095](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16095)

Represents a HydratedTemplateButton.

## Implements

- [`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

## Constructors

### new HydratedTemplateButton()

> **new HydratedTemplateButton**(`properties`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:16101](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16101)

Constructs a new HydratedTemplateButton.

#### Parameters

##### properties?

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

Properties to set

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

## Properties

### callButton?

> `optional` **callButton**: `null` \| [`IHydratedCallButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedCallButton.md)

Defined in: [WAProto/index.d.ts:16113](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16113)

HydratedTemplateButton callButton.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`callButton`](../interfaces/IHydratedTemplateButton.md#callbutton)

***

### hydratedButton?

> `optional` **hydratedButton**: `"quickReplyButton"` \| `"urlButton"` \| `"callButton"`

Defined in: [WAProto/index.d.ts:16116](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16116)

HydratedTemplateButton hydratedButton.

***

### index?

> `optional` **index**: `null` \| `number`

Defined in: [WAProto/index.d.ts:16104](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16104)

HydratedTemplateButton index.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`index`](../interfaces/IHydratedTemplateButton.md#index)

***

### quickReplyButton?

> `optional` **quickReplyButton**: `null` \| [`IHydratedQuickReplyButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:16107](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16107)

HydratedTemplateButton quickReplyButton.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`quickReplyButton`](../interfaces/IHydratedTemplateButton.md#quickreplybutton)

***

### urlButton?

> `optional` **urlButton**: `null` \| [`IHydratedURLButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedURLButton.md)

Defined in: [WAProto/index.d.ts:16110](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16110)

HydratedTemplateButton urlButton.

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`urlButton`](../interfaces/IHydratedTemplateButton.md#urlbutton)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16186](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16186)

Converts this HydratedTemplateButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:16123](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16123)

Creates a new HydratedTemplateButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

Properties to set

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:16149](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16149)

Decodes a HydratedTemplateButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:16158](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16158)

Decodes a HydratedTemplateButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16131](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16131)

Encodes the specified HydratedTemplateButton message. Does not implicitly [verify](HydratedTemplateButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

HydratedTemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16139](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16139)

Encodes the specified HydratedTemplateButton message, length delimited. Does not implicitly [verify](HydratedTemplateButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

HydratedTemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:16172](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16172)

Creates a HydratedTemplateButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:16193](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16193)

Gets the default type url for HydratedTemplateButton

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

Defined in: [WAProto/index.d.ts:16180](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16180)

Creates a plain object from a HydratedTemplateButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedTemplateButton`](HydratedTemplateButton.md)

HydratedTemplateButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16165](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L16165)

Verifies a HydratedTemplateButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
