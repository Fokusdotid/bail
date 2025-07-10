# Class: AIRichResponseMessage

Defined in: [WAProto/index.d.ts:710](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L710)

Represents a AIRichResponseMessage.

## Implements

- [`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

## Constructors

### new AIRichResponseMessage()

> **new AIRichResponseMessage**(`properties`?): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:716](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L716)

Constructs a new AIRichResponseMessage.

#### Parameters

##### properties?

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

Properties to set

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

## Properties

### messageType?

> `optional` **messageType**: `null` \| [`AIRichResponseMessageType`](../namespaces/AIRichResponseMessage/enumerations/AIRichResponseMessageType.md)

Defined in: [WAProto/index.d.ts:719](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L719)

AIRichResponseMessage messageType.

#### Implementation of

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md).[`messageType`](../interfaces/IAIRichResponseMessage.md#messagetype)

***

### submessages

> **submessages**: [`IAIRichResponseSubMessage`](../namespaces/AIRichResponseMessage/interfaces/IAIRichResponseSubMessage.md)[]

Defined in: [WAProto/index.d.ts:722](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L722)

AIRichResponseMessage submessages.

#### Implementation of

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md).[`submessages`](../interfaces/IAIRichResponseMessage.md#submessages)

***

### unifiedResponse?

> `optional` **unifiedResponse**: `null` \| [`IAIRichResponseUnifiedResponse`](../namespaces/AIRichResponseMessage/interfaces/IAIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:725](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L725)

AIRichResponseMessage unifiedResponse.

#### Implementation of

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md).[`unifiedResponse`](../interfaces/IAIRichResponseMessage.md#unifiedresponse)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:795](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L795)

Converts this AIRichResponseMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:732](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L732)

Creates a new AIRichResponseMessage instance using the specified properties.

#### Parameters

##### properties?

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

Properties to set

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

AIRichResponseMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:758](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L758)

Decodes a AIRichResponseMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

AIRichResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:767](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L767)

Decodes a AIRichResponseMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

AIRichResponseMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:740](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L740)

Encodes the specified AIRichResponseMessage message. Does not implicitly [verify](AIRichResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

AIRichResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:748](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L748)

Encodes the specified AIRichResponseMessage message, length delimited. Does not implicitly [verify](AIRichResponseMessage.md#verify) messages.

#### Parameters

##### message

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

AIRichResponseMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:781](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L781)

Creates a AIRichResponseMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

AIRichResponseMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:802](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L802)

Gets the default type url for AIRichResponseMessage

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

Defined in: [WAProto/index.d.ts:789](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L789)

Creates a plain object from a AIRichResponseMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIRichResponseMessage`](AIRichResponseMessage.md)

AIRichResponseMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:774](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L774)

Verifies a AIRichResponseMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
