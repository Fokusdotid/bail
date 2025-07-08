# Class: WaffleNonceFetchResponse

Defined in: [WAProto/index.d.ts:30954](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30954)

Represents a WaffleNonceFetchResponse.

## Implements

- [`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

## Constructors

### new WaffleNonceFetchResponse()

> **new WaffleNonceFetchResponse**(`properties`?): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30960](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30960)

Constructs a new WaffleNonceFetchResponse.

#### Parameters

##### properties?

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

Properties to set

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

## Properties

### nonce?

> `optional` **nonce**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30963](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30963)

WaffleNonceFetchResponse nonce.

#### Implementation of

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md).[`nonce`](../interfaces/IWaffleNonceFetchResponse.md#nonce)

***

### waEntFbid?

> `optional` **waEntFbid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:30966](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30966)

WaffleNonceFetchResponse waEntFbid.

#### Implementation of

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md).[`waEntFbid`](../interfaces/IWaffleNonceFetchResponse.md#waentfbid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:31036](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L31036)

Converts this WaffleNonceFetchResponse to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30973](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30973)

Creates a new WaffleNonceFetchResponse instance using the specified properties.

#### Parameters

##### properties?

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

Properties to set

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

WaffleNonceFetchResponse instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:30999](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30999)

Decodes a WaffleNonceFetchResponse message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

WaffleNonceFetchResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:31008](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L31008)

Decodes a WaffleNonceFetchResponse message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

WaffleNonceFetchResponse

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30981](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30981)

Encodes the specified WaffleNonceFetchResponse message. Does not implicitly [verify](WaffleNonceFetchResponse.md#verify) messages.

#### Parameters

##### message

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

WaffleNonceFetchResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:30989](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L30989)

Encodes the specified WaffleNonceFetchResponse message, length delimited. Does not implicitly [verify](WaffleNonceFetchResponse.md#verify) messages.

#### Parameters

##### message

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

WaffleNonceFetchResponse message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:31022](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L31022)

Creates a WaffleNonceFetchResponse message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

WaffleNonceFetchResponse

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:31043](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L31043)

Gets the default type url for WaffleNonceFetchResponse

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

Defined in: [WAProto/index.d.ts:31030](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L31030)

Creates a plain object from a WaffleNonceFetchResponse message. Also converts values to other types if specified.

#### Parameters

##### message

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

WaffleNonceFetchResponse

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:31015](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L31015)

Verifies a WaffleNonceFetchResponse message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
