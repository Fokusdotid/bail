# Class: Footer

Defined in: [WAProto/index.d.ts:25414](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25414)

Represents a Footer.

## Implements

- [`IFooter`](../interfaces/IFooter.md)

## Constructors

### new Footer()

> **new Footer**(`properties`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:25420](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25420)

Constructs a new Footer.

#### Parameters

##### properties?

[`IFooter`](../interfaces/IFooter.md)

Properties to set

#### Returns

[`Footer`](Footer.md)

## Properties

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:25423](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25423)

Footer text.

#### Implementation of

[`IFooter`](../interfaces/IFooter.md).[`text`](../interfaces/IFooter.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25493](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25493)

Converts this Footer to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:25430](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25430)

Creates a new Footer instance using the specified properties.

#### Parameters

##### properties?

[`IFooter`](../interfaces/IFooter.md)

Properties to set

#### Returns

[`Footer`](Footer.md)

Footer instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:25456](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25456)

Decodes a Footer message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Footer`](Footer.md)

Footer

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:25465](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25465)

Decodes a Footer message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Footer`](Footer.md)

Footer

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25438](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25438)

Encodes the specified Footer message. Does not implicitly [verify](Footer.md#verify) messages.

#### Parameters

##### message

[`IFooter`](../interfaces/IFooter.md)

Footer message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25446](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25446)

Encodes the specified Footer message, length delimited. Does not implicitly [verify](Footer.md#verify) messages.

#### Parameters

##### message

[`IFooter`](../interfaces/IFooter.md)

Footer message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:25479](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25479)

Creates a Footer message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Footer`](Footer.md)

Footer

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:25500](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25500)

Gets the default type url for Footer

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

Defined in: [WAProto/index.d.ts:25487](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25487)

Creates a plain object from a Footer message. Also converts values to other types if specified.

#### Parameters

##### message

[`Footer`](Footer.md)

Footer

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25472](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L25472)

Verifies a Footer message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
