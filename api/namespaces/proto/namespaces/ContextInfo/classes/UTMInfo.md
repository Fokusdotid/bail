# Class: UTMInfo

Defined in: [WAProto/index.d.ts:12218](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12218)

Represents a UTMInfo.

## Implements

- [`IUTMInfo`](../interfaces/IUTMInfo.md)

## Constructors

### new UTMInfo()

> **new UTMInfo**(`properties`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:12224](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12224)

Constructs a new UTMInfo.

#### Parameters

##### properties?

[`IUTMInfo`](../interfaces/IUTMInfo.md)

Properties to set

#### Returns

[`UTMInfo`](UTMInfo.md)

## Properties

### utmCampaign?

> `optional` **utmCampaign**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12230](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12230)

UTMInfo utmCampaign.

#### Implementation of

[`IUTMInfo`](../interfaces/IUTMInfo.md).[`utmCampaign`](../interfaces/IUTMInfo.md#utmcampaign)

***

### utmSource?

> `optional` **utmSource**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12227](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12227)

UTMInfo utmSource.

#### Implementation of

[`IUTMInfo`](../interfaces/IUTMInfo.md).[`utmSource`](../interfaces/IUTMInfo.md#utmsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12300](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12300)

Converts this UTMInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:12237](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12237)

Creates a new UTMInfo instance using the specified properties.

#### Parameters

##### properties?

[`IUTMInfo`](../interfaces/IUTMInfo.md)

Properties to set

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:12263](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12263)

Decodes a UTMInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:12272](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12272)

Decodes a UTMInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12245](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12245)

Encodes the specified UTMInfo message. Does not implicitly [verify](UTMInfo.md#verify) messages.

#### Parameters

##### message

[`IUTMInfo`](../interfaces/IUTMInfo.md)

UTMInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:12253](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12253)

Encodes the specified UTMInfo message, length delimited. Does not implicitly [verify](UTMInfo.md#verify) messages.

#### Parameters

##### message

[`IUTMInfo`](../interfaces/IUTMInfo.md)

UTMInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:12286](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12286)

Creates a UTMInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UTMInfo`](UTMInfo.md)

UTMInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12307](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12307)

Gets the default type url for UTMInfo

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

Defined in: [WAProto/index.d.ts:12294](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12294)

Creates a plain object from a UTMInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`UTMInfo`](UTMInfo.md)

UTMInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:12279](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L12279)

Verifies a UTMInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
