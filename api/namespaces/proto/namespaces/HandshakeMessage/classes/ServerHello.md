# Class: ServerHello

Defined in: [WAProto/index.d.ts:15666](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15666)

Represents a ServerHello.

## Implements

- [`IServerHello`](../interfaces/IServerHello.md)

## Constructors

### new ServerHello()

> **new ServerHello**(`properties`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:15672](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15672)

Constructs a new ServerHello.

#### Parameters

##### properties?

[`IServerHello`](../interfaces/IServerHello.md)

Properties to set

#### Returns

[`ServerHello`](ServerHello.md)

## Properties

### ephemeral?

> `optional` **ephemeral**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15675](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15675)

ServerHello ephemeral.

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`ephemeral`](../interfaces/IServerHello.md#ephemeral)

***

### payload?

> `optional` **payload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15681](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15681)

ServerHello payload.

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`payload`](../interfaces/IServerHello.md#payload)

***

### static?

> `optional` **static**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:15678](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15678)

ServerHello static.

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`static`](../interfaces/IServerHello.md#static)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15751](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15751)

Converts this ServerHello to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:15688](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15688)

Creates a new ServerHello instance using the specified properties.

#### Parameters

##### properties?

[`IServerHello`](../interfaces/IServerHello.md)

Properties to set

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:15714](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15714)

Decodes a ServerHello message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:15723](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15723)

Decodes a ServerHello message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15696](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15696)

Encodes the specified ServerHello message. Does not implicitly [verify](ServerHello.md#verify) messages.

#### Parameters

##### message

[`IServerHello`](../interfaces/IServerHello.md)

ServerHello message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15704](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15704)

Encodes the specified ServerHello message, length delimited. Does not implicitly [verify](ServerHello.md#verify) messages.

#### Parameters

##### message

[`IServerHello`](../interfaces/IServerHello.md)

ServerHello message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:15737](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15737)

Creates a ServerHello message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ServerHello`](ServerHello.md)

ServerHello

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:15758](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15758)

Gets the default type url for ServerHello

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

Defined in: [WAProto/index.d.ts:15745](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15745)

Creates a plain object from a ServerHello message. Also converts values to other types if specified.

#### Parameters

##### message

[`ServerHello`](ServerHello.md)

ServerHello

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15730](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L15730)

Verifies a ServerHello message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
