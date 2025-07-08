# Class: AndroidUnsupportedActions

Defined in: [WAProto/index.d.ts:43794](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43794)

Represents an AndroidUnsupportedActions.

## Implements

- [`IAndroidUnsupportedActions`](../interfaces/IAndroidUnsupportedActions.md)

## Constructors

### new AndroidUnsupportedActions()

> **new AndroidUnsupportedActions**(`properties`?): [`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

Defined in: [WAProto/index.d.ts:43800](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43800)

Constructs a new AndroidUnsupportedActions.

#### Parameters

##### properties?

[`IAndroidUnsupportedActions`](../interfaces/IAndroidUnsupportedActions.md)

Properties to set

#### Returns

[`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

## Properties

### allowed?

> `optional` **allowed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:43803](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43803)

AndroidUnsupportedActions allowed.

#### Implementation of

[`IAndroidUnsupportedActions`](../interfaces/IAndroidUnsupportedActions.md).[`allowed`](../interfaces/IAndroidUnsupportedActions.md#allowed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:43873](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43873)

Converts this AndroidUnsupportedActions to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

Defined in: [WAProto/index.d.ts:43810](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43810)

Creates a new AndroidUnsupportedActions instance using the specified properties.

#### Parameters

##### properties?

[`IAndroidUnsupportedActions`](../interfaces/IAndroidUnsupportedActions.md)

Properties to set

#### Returns

[`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

AndroidUnsupportedActions instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

Defined in: [WAProto/index.d.ts:43836](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43836)

Decodes an AndroidUnsupportedActions message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

AndroidUnsupportedActions

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

Defined in: [WAProto/index.d.ts:43845](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43845)

Decodes an AndroidUnsupportedActions message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

AndroidUnsupportedActions

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:43818](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43818)

Encodes the specified AndroidUnsupportedActions message. Does not implicitly [verify](AndroidUnsupportedActions.md#verify) messages.

#### Parameters

##### message

[`IAndroidUnsupportedActions`](../interfaces/IAndroidUnsupportedActions.md)

AndroidUnsupportedActions message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:43826](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43826)

Encodes the specified AndroidUnsupportedActions message, length delimited. Does not implicitly [verify](AndroidUnsupportedActions.md#verify) messages.

#### Parameters

##### message

[`IAndroidUnsupportedActions`](../interfaces/IAndroidUnsupportedActions.md)

AndroidUnsupportedActions message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

Defined in: [WAProto/index.d.ts:43859](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43859)

Creates an AndroidUnsupportedActions message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

AndroidUnsupportedActions

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:43880](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43880)

Gets the default type url for AndroidUnsupportedActions

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

Defined in: [WAProto/index.d.ts:43867](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43867)

Creates a plain object from an AndroidUnsupportedActions message. Also converts values to other types if specified.

#### Parameters

##### message

[`AndroidUnsupportedActions`](AndroidUnsupportedActions.md)

AndroidUnsupportedActions

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:43852](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L43852)

Verifies an AndroidUnsupportedActions message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
