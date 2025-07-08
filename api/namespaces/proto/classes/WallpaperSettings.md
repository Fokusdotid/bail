# Class: WallpaperSettings

Defined in: [WAProto/index.d.ts:52188](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52188)

Represents a WallpaperSettings.

## Implements

- [`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

## Constructors

### new WallpaperSettings()

> **new WallpaperSettings**(`properties`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:52194](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52194)

Constructs a new WallpaperSettings.

#### Parameters

##### properties?

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

Properties to set

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

## Properties

### filename?

> `optional` **filename**: `null` \| `string`

Defined in: [WAProto/index.d.ts:52197](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52197)

WallpaperSettings filename.

#### Implementation of

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md).[`filename`](../interfaces/IWallpaperSettings.md#filename)

***

### opacity?

> `optional` **opacity**: `null` \| `number`

Defined in: [WAProto/index.d.ts:52200](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52200)

WallpaperSettings opacity.

#### Implementation of

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md).[`opacity`](../interfaces/IWallpaperSettings.md#opacity)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:52270](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52270)

Converts this WallpaperSettings to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:52207](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52207)

Creates a new WallpaperSettings instance using the specified properties.

#### Parameters

##### properties?

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

Properties to set

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:52233](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52233)

Decodes a WallpaperSettings message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:52242](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52242)

Decodes a WallpaperSettings message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:52215](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52215)

Encodes the specified WallpaperSettings message. Does not implicitly [verify](WallpaperSettings.md#verify) messages.

#### Parameters

##### message

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

WallpaperSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:52223](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52223)

Encodes the specified WallpaperSettings message, length delimited. Does not implicitly [verify](WallpaperSettings.md#verify) messages.

#### Parameters

##### message

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

WallpaperSettings message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:52256](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52256)

Creates a WallpaperSettings message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:52277](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52277)

Gets the default type url for WallpaperSettings

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

Defined in: [WAProto/index.d.ts:52264](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52264)

Creates a plain object from a WallpaperSettings message. Also converts values to other types if specified.

#### Parameters

##### message

[`WallpaperSettings`](WallpaperSettings.md)

WallpaperSettings

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:52249](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L52249)

Verifies a WallpaperSettings message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
