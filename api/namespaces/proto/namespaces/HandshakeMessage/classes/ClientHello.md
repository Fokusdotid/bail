# Class: ClientHello

Defined in: [WAProto/index.d.ts:15557](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15557)

Represents a ClientHello.

## Implements

- [`IClientHello`](../interfaces/IClientHello.md)

## Constructors

### new ClientHello()

> **new ClientHello**(`properties`?): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:15563](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15563)

Constructs a new ClientHello.

#### Parameters

##### properties?

[`IClientHello`](../interfaces/IClientHello.md)

Properties to set

#### Returns

[`ClientHello`](ClientHello.md)

## Properties

### ephemeral?

> `optional` **ephemeral**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15566](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15566)

ClientHello ephemeral.

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`ephemeral`](../interfaces/IClientHello.md#ephemeral)

***

### payload?

> `optional` **payload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15572](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15572)

ClientHello payload.

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`payload`](../interfaces/IClientHello.md#payload)

***

### static?

> `optional` **static**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15569](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15569)

ClientHello static.

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`static`](../interfaces/IClientHello.md#static)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15642](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15642)

Converts this ClientHello to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:15579](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15579)

Creates a new ClientHello instance using the specified properties.

#### Parameters

##### properties?

[`IClientHello`](../interfaces/IClientHello.md)

Properties to set

#### Returns

[`ClientHello`](ClientHello.md)

ClientHello instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:15605](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15605)

Decodes a ClientHello message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ClientHello`](ClientHello.md)

ClientHello

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:15614](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15614)

Decodes a ClientHello message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ClientHello`](ClientHello.md)

ClientHello

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15587](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15587)

Encodes the specified ClientHello message. Does not implicitly [verify](ClientHello.md#verify) messages.

#### Parameters

##### message

[`IClientHello`](../interfaces/IClientHello.md)

ClientHello message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15595](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15595)

Encodes the specified ClientHello message, length delimited. Does not implicitly [verify](ClientHello.md#verify) messages.

#### Parameters

##### message

[`IClientHello`](../interfaces/IClientHello.md)

ClientHello message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:15628](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15628)

Creates a ClientHello message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ClientHello`](ClientHello.md)

ClientHello

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:15649](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15649)

Gets the default type url for ClientHello

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

Defined in: [WAProto/index.d.ts:15636](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15636)

Creates a plain object from a ClientHello message. Also converts values to other types if specified.

#### Parameters

##### message

[`ClientHello`](ClientHello.md)

ClientHello

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15621](https://github.com/Fokusdotid/bail/blob/3bd64a6fd6e8fc52d3ec9ba842534bed26103555/WAProto/index.d.ts#L15621)

Verifies a ClientHello message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
