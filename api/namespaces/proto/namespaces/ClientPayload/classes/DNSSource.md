# Class: DNSSource

Defined in: [WAProto/index.d.ts:9296](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9296)

Represents a DNSSource.

## Implements

- [`IDNSSource`](../interfaces/IDNSSource.md)

## Constructors

### new DNSSource()

> **new DNSSource**(`properties`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:9302](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9302)

Constructs a new DNSSource.

#### Parameters

##### properties?

[`IDNSSource`](../interfaces/IDNSSource.md)

Properties to set

#### Returns

[`DNSSource`](DNSSource.md)

## Properties

### appCached?

> `optional` **appCached**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:9308](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9308)

DNSSource appCached.

#### Implementation of

[`IDNSSource`](../interfaces/IDNSSource.md).[`appCached`](../interfaces/IDNSSource.md#appcached)

***

### dnsMethod?

> `optional` **dnsMethod**: `null` \| [`DNSResolutionMethod`](../namespaces/DNSSource/enumerations/DNSResolutionMethod.md)

Defined in: [WAProto/index.d.ts:9305](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9305)

DNSSource dnsMethod.

#### Implementation of

[`IDNSSource`](../interfaces/IDNSSource.md).[`dnsMethod`](../interfaces/IDNSSource.md#dnsmethod)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9378](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9378)

Converts this DNSSource to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:9315](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9315)

Creates a new DNSSource instance using the specified properties.

#### Parameters

##### properties?

[`IDNSSource`](../interfaces/IDNSSource.md)

Properties to set

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:9341](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9341)

Decodes a DNSSource message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:9350](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9350)

Decodes a DNSSource message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9323](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9323)

Encodes the specified DNSSource message. Does not implicitly [verify](DNSSource.md#verify) messages.

#### Parameters

##### message

[`IDNSSource`](../interfaces/IDNSSource.md)

DNSSource message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9331](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9331)

Encodes the specified DNSSource message, length delimited. Does not implicitly [verify](DNSSource.md#verify) messages.

#### Parameters

##### message

[`IDNSSource`](../interfaces/IDNSSource.md)

DNSSource message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:9364](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9364)

Creates a DNSSource message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`DNSSource`](DNSSource.md)

DNSSource

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9385](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9385)

Gets the default type url for DNSSource

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

Defined in: [WAProto/index.d.ts:9372](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9372)

Creates a plain object from a DNSSource message. Also converts values to other types if specified.

#### Parameters

##### message

[`DNSSource`](DNSSource.md)

DNSSource

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:9357](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L9357)

Verifies a DNSSource message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
