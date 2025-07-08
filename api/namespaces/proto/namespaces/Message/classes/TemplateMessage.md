# Class: TemplateMessage

Defined in: [WAProto/index.d.ts:34796](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34796)

Represents a TemplateMessage.

## Implements

- [`ITemplateMessage`](../interfaces/ITemplateMessage.md)

## Constructors

### new TemplateMessage()

> **new TemplateMessage**(`properties`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:34802](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34802)

Constructs a new TemplateMessage.

#### Parameters

##### properties?

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

Properties to set

#### Returns

[`TemplateMessage`](TemplateMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:34805](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34805)

TemplateMessage contextInfo.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`contextInfo`](../interfaces/ITemplateMessage.md#contextinfo)

***

### format?

> `optional` **format**: `"hydratedFourRowTemplate"` \| `"fourRowTemplate"` \| `"interactiveMessageTemplate"`

Defined in: [WAProto/index.d.ts:34823](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34823)

TemplateMessage format.

***

### fourRowTemplate?

> `optional` **fourRowTemplate**: `null` \| [`IFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:34814](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34814)

TemplateMessage fourRowTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`fourRowTemplate`](../interfaces/ITemplateMessage.md#fourrowtemplate)

***

### hydratedFourRowTemplate?

> `optional` **hydratedFourRowTemplate**: `null` \| [`IHydratedFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IHydratedFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:34817](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34817)

TemplateMessage hydratedFourRowTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`hydratedFourRowTemplate`](../interfaces/ITemplateMessage.md#hydratedfourrowtemplate)

***

### hydratedTemplate?

> `optional` **hydratedTemplate**: `null` \| [`IHydratedFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IHydratedFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:34808](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34808)

TemplateMessage hydratedTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`hydratedTemplate`](../interfaces/ITemplateMessage.md#hydratedtemplate)

***

### interactiveMessageTemplate?

> `optional` **interactiveMessageTemplate**: `null` \| [`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

Defined in: [WAProto/index.d.ts:34820](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34820)

TemplateMessage interactiveMessageTemplate.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`interactiveMessageTemplate`](../interfaces/ITemplateMessage.md#interactivemessagetemplate)

***

### templateId?

> `optional` **templateId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:34811](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34811)

TemplateMessage templateId.

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`templateId`](../interfaces/ITemplateMessage.md#templateid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:34893](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34893)

Converts this TemplateMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:34830](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34830)

Creates a new TemplateMessage instance using the specified properties.

#### Parameters

##### properties?

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

Properties to set

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:34856](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34856)

Decodes a TemplateMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:34865](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34865)

Decodes a TemplateMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34838](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34838)

Encodes the specified TemplateMessage message. Does not implicitly [verify](TemplateMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

TemplateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:34846](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34846)

Encodes the specified TemplateMessage message, length delimited. Does not implicitly [verify](TemplateMessage.md#verify) messages.

#### Parameters

##### message

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

TemplateMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:34879](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34879)

Creates a TemplateMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:34900](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34900)

Gets the default type url for TemplateMessage

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

Defined in: [WAProto/index.d.ts:34887](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34887)

Creates a plain object from a TemplateMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`TemplateMessage`](TemplateMessage.md)

TemplateMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:34872](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L34872)

Verifies a TemplateMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
