# Class: AutoDownloadSettings

Defined in: [WAProto/index.d.ts:3024](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3024)

Represents an AutoDownloadSettings.

## Implements

- [`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

## Constructors

### new AutoDownloadSettings()

> **new AutoDownloadSettings**(`properties`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:3030](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3030)

Constructs a new AutoDownloadSettings.

#### Parameters

##### properties?

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

Properties to set

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

## Properties

### downloadAudio?

> `optional` **downloadAudio**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3036](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3036)

AutoDownloadSettings downloadAudio.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadAudio`](../interfaces/IAutoDownloadSettings.md#downloadaudio)

***

### downloadDocuments?

> `optional` **downloadDocuments**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3042](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3042)

AutoDownloadSettings downloadDocuments.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadDocuments`](../interfaces/IAutoDownloadSettings.md#downloaddocuments)

***

### downloadImages?

> `optional` **downloadImages**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3033](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3033)

AutoDownloadSettings downloadImages.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadImages`](../interfaces/IAutoDownloadSettings.md#downloadimages)

***

### downloadVideo?

> `optional` **downloadVideo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3039](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3039)

AutoDownloadSettings downloadVideo.

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadVideo`](../interfaces/IAutoDownloadSettings.md#downloadvideo)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3112](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3112)

Converts this AutoDownloadSettings to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:3049](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3049)

Creates a new AutoDownloadSettings instance using the specified properties.

#### Parameters

##### properties?

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

Properties to set

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:3075](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3075)

Decodes an AutoDownloadSettings message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:3084](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3084)

Decodes an AutoDownloadSettings message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3057](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3057)

Encodes the specified AutoDownloadSettings message. Does not implicitly [verify](AutoDownloadSettings.md#verify) messages.

#### Parameters

##### message

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

AutoDownloadSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:3065](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3065)

Encodes the specified AutoDownloadSettings message, length delimited. Does not implicitly [verify](AutoDownloadSettings.md#verify) messages.

#### Parameters

##### message

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

AutoDownloadSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:3098](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3098)

Creates an AutoDownloadSettings message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3119](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3119)

Gets the default type url for AutoDownloadSettings

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

Defined in: [WAProto/index.d.ts:3106](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3106)

Creates a plain object from an AutoDownloadSettings message. Also converts values to other types if specified.

#### Parameters

##### message

[`AutoDownloadSettings`](AutoDownloadSettings.md)

AutoDownloadSettings

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:3091](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3091)

Verifies an AutoDownloadSettings message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
