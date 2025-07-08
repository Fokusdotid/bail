# Class: ActionLink

Defined in: [WAProto/index.d.ts:2915](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2915)

Represents an ActionLink.

## Implements

- [`IActionLink`](../interfaces/IActionLink.md)

## Constructors

### new ActionLink()

> **new ActionLink**(`properties`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:2921](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2921)

Constructs a new ActionLink.

#### Parameters

##### properties?

[`IActionLink`](../interfaces/IActionLink.md)

Properties to set

#### Returns

[`ActionLink`](ActionLink.md)

## Properties

### buttonTitle?

> `optional` **buttonTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2927](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2927)

ActionLink buttonTitle.

#### Implementation of

[`IActionLink`](../interfaces/IActionLink.md).[`buttonTitle`](../interfaces/IActionLink.md#buttontitle)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2924](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2924)

ActionLink url.

#### Implementation of

[`IActionLink`](../interfaces/IActionLink.md).[`url`](../interfaces/IActionLink.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2997](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2997)

Converts this ActionLink to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:2934](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2934)

Creates a new ActionLink instance using the specified properties.

#### Parameters

##### properties?

[`IActionLink`](../interfaces/IActionLink.md)

Properties to set

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:2960](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2960)

Decodes an ActionLink message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:2969](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2969)

Decodes an ActionLink message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2942](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2942)

Encodes the specified ActionLink message. Does not implicitly [verify](ActionLink.md#verify) messages.

#### Parameters

##### message

[`IActionLink`](../interfaces/IActionLink.md)

ActionLink message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:2950](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2950)

Encodes the specified ActionLink message, length delimited. Does not implicitly [verify](ActionLink.md#verify) messages.

#### Parameters

##### message

[`IActionLink`](../interfaces/IActionLink.md)

ActionLink message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:2983](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2983)

Creates an ActionLink message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ActionLink`](ActionLink.md)

ActionLink

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3004](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L3004)

Gets the default type url for ActionLink

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

Defined in: [WAProto/index.d.ts:2991](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2991)

Creates a plain object from an ActionLink message. Also converts values to other types if specified.

#### Parameters

##### message

[`ActionLink`](ActionLink.md)

ActionLink

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:2976](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L2976)

Verifies an ActionLink message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
