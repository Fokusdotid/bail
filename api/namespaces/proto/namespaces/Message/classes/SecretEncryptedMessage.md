# Class: SecretEncryptedMessage

Defined in: [WAProto/index.d.ts:33533](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33533)

Represents a SecretEncryptedMessage.

## Implements

- [`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

## Constructors

### new SecretEncryptedMessage()

> **new SecretEncryptedMessage**(`properties`?): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:33539](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33539)

Constructs a new SecretEncryptedMessage.

#### Parameters

##### properties?

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

Properties to set

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:33548](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33548)

SecretEncryptedMessage encIv.

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`encIv`](../interfaces/ISecretEncryptedMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:33545](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33545)

SecretEncryptedMessage encPayload.

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`encPayload`](../interfaces/ISecretEncryptedMessage.md#encpayload)

***

### secretEncType?

> `optional` **secretEncType**: `null` \| [`SecretEncType`](../namespaces/SecretEncryptedMessage/enumerations/SecretEncType.md)

Defined in: [WAProto/index.d.ts:33551](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33551)

SecretEncryptedMessage secretEncType.

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`secretEncType`](../interfaces/ISecretEncryptedMessage.md#secretenctype)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:33542](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33542)

SecretEncryptedMessage targetMessageKey.

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`targetMessageKey`](../interfaces/ISecretEncryptedMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:33621](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33621)

Converts this SecretEncryptedMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:33558](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33558)

Creates a new SecretEncryptedMessage instance using the specified properties.

#### Parameters

##### properties?

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

Properties to set

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

SecretEncryptedMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:33584](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33584)

Decodes a SecretEncryptedMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

SecretEncryptedMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:33593](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33593)

Decodes a SecretEncryptedMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

SecretEncryptedMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33566](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33566)

Encodes the specified SecretEncryptedMessage message. Does not implicitly [verify](SecretEncryptedMessage.md#verify) messages.

#### Parameters

##### message

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

SecretEncryptedMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:33574](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33574)

Encodes the specified SecretEncryptedMessage message, length delimited. Does not implicitly [verify](SecretEncryptedMessage.md#verify) messages.

#### Parameters

##### message

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

SecretEncryptedMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:33607](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33607)

Creates a SecretEncryptedMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

SecretEncryptedMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:33628](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33628)

Gets the default type url for SecretEncryptedMessage

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

Defined in: [WAProto/index.d.ts:33615](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33615)

Creates a plain object from a SecretEncryptedMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

SecretEncryptedMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:33600](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L33600)

Verifies a SecretEncryptedMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
