# Class: UrlTrackingMapElement

Defined in: [WAProto/index.d.ts:51375](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51375)

Represents an UrlTrackingMapElement.

## Implements

- [`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md)

## Constructors

### new UrlTrackingMapElement()

> **new UrlTrackingMapElement**(`properties`?): [`UrlTrackingMapElement`](UrlTrackingMapElement.md)

Defined in: [WAProto/index.d.ts:51381](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51381)

Constructs a new UrlTrackingMapElement.

#### Parameters

##### properties?

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md)

Properties to set

#### Returns

[`UrlTrackingMapElement`](UrlTrackingMapElement.md)

## Properties

### cardIndex?

> `optional` **cardIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:51393](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51393)

UrlTrackingMapElement cardIndex.

#### Implementation of

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md).[`cardIndex`](../interfaces/IUrlTrackingMapElement.md#cardindex)

***

### consentedUsersUrl?

> `optional` **consentedUsersUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:51390](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51390)

UrlTrackingMapElement consentedUsersUrl.

#### Implementation of

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md).[`consentedUsersUrl`](../interfaces/IUrlTrackingMapElement.md#consentedusersurl)

***

### originalUrl?

> `optional` **originalUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:51384](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51384)

UrlTrackingMapElement originalUrl.

#### Implementation of

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md).[`originalUrl`](../interfaces/IUrlTrackingMapElement.md#originalurl)

***

### unconsentedUsersUrl?

> `optional` **unconsentedUsersUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:51387](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51387)

UrlTrackingMapElement unconsentedUsersUrl.

#### Implementation of

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md).[`unconsentedUsersUrl`](../interfaces/IUrlTrackingMapElement.md#unconsentedusersurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51463](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51463)

Converts this UrlTrackingMapElement to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UrlTrackingMapElement`](UrlTrackingMapElement.md)

Defined in: [WAProto/index.d.ts:51400](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51400)

Creates a new UrlTrackingMapElement instance using the specified properties.

#### Parameters

##### properties?

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md)

Properties to set

#### Returns

[`UrlTrackingMapElement`](UrlTrackingMapElement.md)

UrlTrackingMapElement instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UrlTrackingMapElement`](UrlTrackingMapElement.md)

Defined in: [WAProto/index.d.ts:51426](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51426)

Decodes an UrlTrackingMapElement message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UrlTrackingMapElement`](UrlTrackingMapElement.md)

UrlTrackingMapElement

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UrlTrackingMapElement`](UrlTrackingMapElement.md)

Defined in: [WAProto/index.d.ts:51435](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51435)

Decodes an UrlTrackingMapElement message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UrlTrackingMapElement`](UrlTrackingMapElement.md)

UrlTrackingMapElement

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51408](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51408)

Encodes the specified UrlTrackingMapElement message. Does not implicitly [verify](UrlTrackingMapElement.md#verify) messages.

#### Parameters

##### message

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md)

UrlTrackingMapElement message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51416](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51416)

Encodes the specified UrlTrackingMapElement message, length delimited. Does not implicitly [verify](UrlTrackingMapElement.md#verify) messages.

#### Parameters

##### message

[`IUrlTrackingMapElement`](../interfaces/IUrlTrackingMapElement.md)

UrlTrackingMapElement message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UrlTrackingMapElement`](UrlTrackingMapElement.md)

Defined in: [WAProto/index.d.ts:51449](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51449)

Creates an UrlTrackingMapElement message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UrlTrackingMapElement`](UrlTrackingMapElement.md)

UrlTrackingMapElement

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51470](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51470)

Gets the default type url for UrlTrackingMapElement

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

Defined in: [WAProto/index.d.ts:51457](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51457)

Creates a plain object from an UrlTrackingMapElement message. Also converts values to other types if specified.

#### Parameters

##### message

[`UrlTrackingMapElement`](UrlTrackingMapElement.md)

UrlTrackingMapElement

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51442](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L51442)

Verifies an UrlTrackingMapElement message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
