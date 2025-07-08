# Class: StarAction

Defined in: [WAProto/index.d.ts:48577](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48577)

Represents a StarAction.

## Implements

- [`IStarAction`](../interfaces/IStarAction.md)

## Constructors

### new StarAction()

> **new StarAction**(`properties`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:48583](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48583)

Constructs a new StarAction.

#### Parameters

##### properties?

[`IStarAction`](../interfaces/IStarAction.md)

Properties to set

#### Returns

[`StarAction`](StarAction.md)

## Properties

### starred?

> `optional` **starred**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:48586](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48586)

StarAction starred.

#### Implementation of

[`IStarAction`](../interfaces/IStarAction.md).[`starred`](../interfaces/IStarAction.md#starred)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:48656](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48656)

Converts this StarAction to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:48593](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48593)

Creates a new StarAction instance using the specified properties.

#### Parameters

##### properties?

[`IStarAction`](../interfaces/IStarAction.md)

Properties to set

#### Returns

[`StarAction`](StarAction.md)

StarAction instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:48619](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48619)

Decodes a StarAction message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StarAction`](StarAction.md)

StarAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:48628](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48628)

Decodes a StarAction message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StarAction`](StarAction.md)

StarAction

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48601](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48601)

Encodes the specified StarAction message. Does not implicitly [verify](StarAction.md#verify) messages.

#### Parameters

##### message

[`IStarAction`](../interfaces/IStarAction.md)

StarAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:48609](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48609)

Encodes the specified StarAction message, length delimited. Does not implicitly [verify](StarAction.md#verify) messages.

#### Parameters

##### message

[`IStarAction`](../interfaces/IStarAction.md)

StarAction message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:48642](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48642)

Creates a StarAction message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StarAction`](StarAction.md)

StarAction

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:48663](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48663)

Gets the default type url for StarAction

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

Defined in: [WAProto/index.d.ts:48650](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48650)

Creates a plain object from a StarAction message. Also converts values to other types if specified.

#### Parameters

##### message

[`StarAction`](StarAction.md)

StarAction

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:48635](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/WAProto/index.d.ts#L48635)

Verifies a StarAction message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
