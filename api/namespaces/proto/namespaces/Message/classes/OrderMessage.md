# Class: OrderMessage

Defined in: [WAProto/index.d.ts:28676](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28676)

Represents an OrderMessage.

## Implements

- [`IOrderMessage`](../interfaces/IOrderMessage.md)

## Constructors

### new OrderMessage()

> **new OrderMessage**(`properties`?): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:28682](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28682)

Constructs a new OrderMessage.

#### Parameters

##### properties?

[`IOrderMessage`](../interfaces/IOrderMessage.md)

Properties to set

#### Returns

[`OrderMessage`](OrderMessage.md)

## Properties

### catalogType?

> `optional` **catalogType**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28727](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28727)

OrderMessage catalogType.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`catalogType`](../interfaces/IOrderMessage.md#catalogtype)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:28718](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28718)

OrderMessage contextInfo.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`contextInfo`](../interfaces/IOrderMessage.md#contextinfo)

***

### itemCount?

> `optional` **itemCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:28691](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28691)

OrderMessage itemCount.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`itemCount`](../interfaces/IOrderMessage.md#itemcount)

***

### message?

> `optional` **message**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28700](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28700)

OrderMessage message.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`message`](../interfaces/IOrderMessage.md#message)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:28721](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28721)

OrderMessage messageVersion.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`messageVersion`](../interfaces/IOrderMessage.md#messageversion)

***

### orderId?

> `optional` **orderId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28685](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28685)

OrderMessage orderId.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`orderId`](../interfaces/IOrderMessage.md#orderid)

***

### orderRequestMessageId?

> `optional` **orderRequestMessageId**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:28724](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28724)

OrderMessage orderRequestMessageId.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`orderRequestMessageId`](../interfaces/IOrderMessage.md#orderrequestmessageid)

***

### orderTitle?

> `optional` **orderTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28703](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28703)

OrderMessage orderTitle.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`orderTitle`](../interfaces/IOrderMessage.md#ordertitle)

***

### sellerJid?

> `optional` **sellerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28706](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28706)

OrderMessage sellerJid.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`sellerJid`](../interfaces/IOrderMessage.md#sellerjid)

***

### status?

> `optional` **status**: `null` \| [`OrderStatus`](../namespaces/OrderMessage/enumerations/OrderStatus.md)

Defined in: [WAProto/index.d.ts:28694](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28694)

OrderMessage status.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`status`](../interfaces/IOrderMessage.md#status)

***

### surface?

> `optional` **surface**: `null` \| [`CATALOG`](../namespaces/OrderMessage/enumerations/OrderSurface.md#catalog)

Defined in: [WAProto/index.d.ts:28697](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28697)

OrderMessage surface.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`surface`](../interfaces/IOrderMessage.md#surface)

***

### thumbnail?

> `optional` **thumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:28688](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28688)

OrderMessage thumbnail.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`thumbnail`](../interfaces/IOrderMessage.md#thumbnail)

***

### token?

> `optional` **token**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28709](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28709)

OrderMessage token.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`token`](../interfaces/IOrderMessage.md#token)

***

### totalAmount1000?

> `optional` **totalAmount1000**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:28712](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28712)

OrderMessage totalAmount1000.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`totalAmount1000`](../interfaces/IOrderMessage.md#totalamount1000)

***

### totalCurrencyCode?

> `optional` **totalCurrencyCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:28715](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28715)

OrderMessage totalCurrencyCode.

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`totalCurrencyCode`](../interfaces/IOrderMessage.md#totalcurrencycode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:28797](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28797)

Converts this OrderMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:28734](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28734)

Creates a new OrderMessage instance using the specified properties.

#### Parameters

##### properties?

[`IOrderMessage`](../interfaces/IOrderMessage.md)

Properties to set

#### Returns

[`OrderMessage`](OrderMessage.md)

OrderMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:28760](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28760)

Decodes an OrderMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`OrderMessage`](OrderMessage.md)

OrderMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:28769](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28769)

Decodes an OrderMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`OrderMessage`](OrderMessage.md)

OrderMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28742](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28742)

Encodes the specified OrderMessage message. Does not implicitly [verify](OrderMessage.md#verify) messages.

#### Parameters

##### message

[`IOrderMessage`](../interfaces/IOrderMessage.md)

OrderMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:28750](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28750)

Encodes the specified OrderMessage message, length delimited. Does not implicitly [verify](OrderMessage.md#verify) messages.

#### Parameters

##### message

[`IOrderMessage`](../interfaces/IOrderMessage.md)

OrderMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:28783](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28783)

Creates an OrderMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`OrderMessage`](OrderMessage.md)

OrderMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:28804](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28804)

Gets the default type url for OrderMessage

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

Defined in: [WAProto/index.d.ts:28791](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28791)

Creates a plain object from an OrderMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`OrderMessage`](OrderMessage.md)

OrderMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:28776](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L28776)

Verifies an OrderMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
