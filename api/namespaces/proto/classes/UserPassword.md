# Class: UserPassword

Defined in: [WAProto/index.d.ts:51491](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51491)

Represents a UserPassword.

## Implements

- [`IUserPassword`](../interfaces/IUserPassword.md)

## Constructors

### new UserPassword()

> **new UserPassword**(`properties`?): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:51497](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51497)

Constructs a new UserPassword.

#### Parameters

##### properties?

[`IUserPassword`](../interfaces/IUserPassword.md)

Properties to set

#### Returns

[`UserPassword`](UserPassword.md)

## Properties

### encoding?

> `optional` **encoding**: `null` \| [`Encoding`](../namespaces/UserPassword/enumerations/Encoding.md)

Defined in: [WAProto/index.d.ts:51500](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51500)

UserPassword encoding.

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`encoding`](../interfaces/IUserPassword.md#encoding)

***

### transformedData?

> `optional` **transformedData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:51509](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51509)

UserPassword transformedData.

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`transformedData`](../interfaces/IUserPassword.md#transformeddata)

***

### transformer?

> `optional` **transformer**: `null` \| [`Transformer`](../namespaces/UserPassword/enumerations/Transformer.md)

Defined in: [WAProto/index.d.ts:51503](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51503)

UserPassword transformer.

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`transformer`](../interfaces/IUserPassword.md#transformer)

***

### transformerArg

> **transformerArg**: [`ITransformerArg`](../namespaces/UserPassword/interfaces/ITransformerArg.md)[]

Defined in: [WAProto/index.d.ts:51506](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51506)

UserPassword transformerArg.

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`transformerArg`](../interfaces/IUserPassword.md#transformerarg)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:51579](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51579)

Converts this UserPassword to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:51516](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51516)

Creates a new UserPassword instance using the specified properties.

#### Parameters

##### properties?

[`IUserPassword`](../interfaces/IUserPassword.md)

Properties to set

#### Returns

[`UserPassword`](UserPassword.md)

UserPassword instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:51542](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51542)

Decodes a UserPassword message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`UserPassword`](UserPassword.md)

UserPassword

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:51551](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51551)

Decodes a UserPassword message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`UserPassword`](UserPassword.md)

UserPassword

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51524](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51524)

Encodes the specified UserPassword message. Does not implicitly [verify](UserPassword.md#verify) messages.

#### Parameters

##### message

[`IUserPassword`](../interfaces/IUserPassword.md)

UserPassword message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:51532](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51532)

Encodes the specified UserPassword message, length delimited. Does not implicitly [verify](UserPassword.md#verify) messages.

#### Parameters

##### message

[`IUserPassword`](../interfaces/IUserPassword.md)

UserPassword message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:51565](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51565)

Creates a UserPassword message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`UserPassword`](UserPassword.md)

UserPassword

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:51586](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51586)

Gets the default type url for UserPassword

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

Defined in: [WAProto/index.d.ts:51573](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51573)

Creates a plain object from a UserPassword message. Also converts values to other types if specified.

#### Parameters

##### message

[`UserPassword`](UserPassword.md)

UserPassword

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:51558](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/WAProto/index.d.ts#L51558)

Verifies a UserPassword message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
