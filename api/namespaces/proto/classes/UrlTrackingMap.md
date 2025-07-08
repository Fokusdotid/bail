# Class: UrlTrackingMap

Defined in: [WAProto/index.d.ts:51267](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51267)

Represents an UrlTrackingMap.

## Implements

- [`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

## Constructors

### new UrlTrackingMap()

> **new UrlTrackingMap**(`properties`?): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:51273](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51273)

Constructs a new UrlTrackingMap.

#### Parameters

##### properties?

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

Properties to set

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

## Properties

### urlTrackingMapElements

> **urlTrackingMapElements**: [`IUrlTrackingMapElement`](../namespaces/UrlTrackingMap/interfaces/IUrlTrackingMapElement.md)[]

Defined in: [WAProto/index.d.ts:51276](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51276)

UrlTrackingMap urlTrackingMapElements.

#### Implementation of

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md).[`urlTrackingMapElements`](../interfaces/IUrlTrackingMap.md#urltrackingmapelements)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51346](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51346)

Converts this UrlTrackingMap to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:51283](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51283)

Creates a new UrlTrackingMap instance using the specified properties.

#### Parameters

##### properties?

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

Properties to set

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

UrlTrackingMap instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:51309](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51309)

Decodes an UrlTrackingMap message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

UrlTrackingMap

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:51318](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51318)

Decodes an UrlTrackingMap message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

UrlTrackingMap

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51291](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51291)

Encodes the specified UrlTrackingMap message. Does not implicitly [verify](UrlTrackingMap.md#verify) messages.

#### Parameters

##### message

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

UrlTrackingMap message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51299](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51299)

Encodes the specified UrlTrackingMap message, length delimited. Does not implicitly [verify](UrlTrackingMap.md#verify) messages.

#### Parameters

##### message

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

UrlTrackingMap message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:51332](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51332)

Creates an UrlTrackingMap message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

UrlTrackingMap

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51353](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51353)

Gets the default type url for UrlTrackingMap

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

Defined in: [WAProto/index.d.ts:51340](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51340)

Creates a plain object from an UrlTrackingMap message. Also converts values to other types if specified.

#### Parameters

##### message

[`UrlTrackingMap`](UrlTrackingMap.md)

UrlTrackingMap

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51325](https://github.com/Fokusdotid/bail/blob/8b525f9ebcc20cb9acd0f880b6ad58976e38b117/WAProto/index.d.ts#L51325)

Verifies an UrlTrackingMap message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
