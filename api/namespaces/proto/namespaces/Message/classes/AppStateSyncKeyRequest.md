# Class: AppStateSyncKeyRequest

Defined in: [WAProto/index.d.ts:19582](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19582)

Represents an AppStateSyncKeyRequest.

## Implements

- [`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

## Constructors

### new AppStateSyncKeyRequest()

> **new AppStateSyncKeyRequest**(`properties`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:19588](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19588)

Constructs a new AppStateSyncKeyRequest.

#### Parameters

##### properties?

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

Properties to set

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

## Properties

### keyIds

> **keyIds**: [`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)[]

Defined in: [WAProto/index.d.ts:19591](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19591)

AppStateSyncKeyRequest keyIds.

#### Implementation of

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md).[`keyIds`](../interfaces/IAppStateSyncKeyRequest.md#keyids)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:19661](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19661)

Converts this AppStateSyncKeyRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:19598](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19598)

Creates a new AppStateSyncKeyRequest instance using the specified properties.

#### Parameters

##### properties?

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

Properties to set

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:19624](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19624)

Decodes an AppStateSyncKeyRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:19633](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19633)

Decodes an AppStateSyncKeyRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19606](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19606)

Encodes the specified AppStateSyncKeyRequest message. Does not implicitly [verify](AppStateSyncKeyRequest.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

AppStateSyncKeyRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:19614](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19614)

Encodes the specified AppStateSyncKeyRequest message, length delimited. Does not implicitly [verify](AppStateSyncKeyRequest.md#verify) messages.

#### Parameters

##### message

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

AppStateSyncKeyRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:19647](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19647)

Creates an AppStateSyncKeyRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:19668](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19668)

Gets the default type url for AppStateSyncKeyRequest

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

Defined in: [WAProto/index.d.ts:19655](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19655)

Creates a plain object from an AppStateSyncKeyRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

AppStateSyncKeyRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:19640](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L19640)

Verifies an AppStateSyncKeyRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
