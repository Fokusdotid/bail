# Class: TemplateButton

Defined in: [WAProto/index.d.ts:50846](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50846)

Represents a TemplateButton.

## Implements

- [`ITemplateButton`](../interfaces/ITemplateButton.md)

## Constructors

### new TemplateButton()

> **new TemplateButton**(`properties`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:50852](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50852)

Constructs a new TemplateButton.

#### Parameters

##### properties?

[`ITemplateButton`](../interfaces/ITemplateButton.md)

Properties to set

#### Returns

[`TemplateButton`](TemplateButton.md)

## Properties

### button?

> `optional` **button**: `"quickReplyButton"` \| `"urlButton"` \| `"callButton"`

Defined in: [WAProto/index.d.ts:50867](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50867)

TemplateButton button.

***

### callButton?

> `optional` **callButton**: `null` \| [`ICallButton`](../namespaces/TemplateButton/interfaces/ICallButton.md)

Defined in: [WAProto/index.d.ts:50864](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50864)

TemplateButton callButton.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`callButton`](../interfaces/ITemplateButton.md#callbutton)

***

### index?

> `optional` **index**: `null` \| `number`

Defined in: [WAProto/index.d.ts:50855](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50855)

TemplateButton index.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`index`](../interfaces/ITemplateButton.md#index)

***

### quickReplyButton?

> `optional` **quickReplyButton**: `null` \| [`IQuickReplyButton`](../namespaces/TemplateButton/interfaces/IQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:50858](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50858)

TemplateButton quickReplyButton.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`quickReplyButton`](../interfaces/ITemplateButton.md#quickreplybutton)

***

### urlButton?

> `optional` **urlButton**: `null` \| [`IURLButton`](../namespaces/TemplateButton/interfaces/IURLButton.md)

Defined in: [WAProto/index.d.ts:50861](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50861)

TemplateButton urlButton.

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`urlButton`](../interfaces/ITemplateButton.md#urlbutton)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:50937](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50937)

Converts this TemplateButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:50874](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50874)

Creates a new TemplateButton instance using the specified properties.

#### Parameters

##### properties?

[`ITemplateButton`](../interfaces/ITemplateButton.md)

Properties to set

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:50900](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50900)

Decodes a TemplateButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:50909](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50909)

Decodes a TemplateButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50882](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50882)

Encodes the specified TemplateButton message. Does not implicitly [verify](TemplateButton.md#verify) messages.

#### Parameters

##### message

[`ITemplateButton`](../interfaces/ITemplateButton.md)

TemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:50890](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50890)

Encodes the specified TemplateButton message, length delimited. Does not implicitly [verify](TemplateButton.md#verify) messages.

#### Parameters

##### message

[`ITemplateButton`](../interfaces/ITemplateButton.md)

TemplateButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:50923](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50923)

Creates a TemplateButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TemplateButton`](TemplateButton.md)

TemplateButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:50944](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50944)

Gets the default type url for TemplateButton

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

Defined in: [WAProto/index.d.ts:50931](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50931)

Creates a plain object from a TemplateButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`TemplateButton`](TemplateButton.md)

TemplateButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:50916](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L50916)

Verifies a TemplateButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
