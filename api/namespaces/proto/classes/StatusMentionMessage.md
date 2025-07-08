# Class: StatusMentionMessage

Defined in: [WAProto/index.d.ts:42772](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42772)

Represents a StatusMentionMessage.

## Implements

- [`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

## Constructors

### new StatusMentionMessage()

> **new StatusMentionMessage**(`properties`?): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:42778](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42778)

Constructs a new StatusMentionMessage.

#### Parameters

##### properties?

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

Properties to set

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

## Properties

### quotedStatus?

> `optional` **quotedStatus**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:42781](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42781)

StatusMentionMessage quotedStatus.

#### Implementation of

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md).[`quotedStatus`](../interfaces/IStatusMentionMessage.md#quotedstatus)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:42851](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42851)

Converts this StatusMentionMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:42788](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42788)

Creates a new StatusMentionMessage instance using the specified properties.

#### Parameters

##### properties?

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

Properties to set

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

StatusMentionMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:42814](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42814)

Decodes a StatusMentionMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

StatusMentionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:42823](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42823)

Decodes a StatusMentionMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

StatusMentionMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42796](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42796)

Encodes the specified StatusMentionMessage message. Does not implicitly [verify](StatusMentionMessage.md#verify) messages.

#### Parameters

##### message

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

StatusMentionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:42804](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42804)

Encodes the specified StatusMentionMessage message, length delimited. Does not implicitly [verify](StatusMentionMessage.md#verify) messages.

#### Parameters

##### message

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

StatusMentionMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:42837](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42837)

Creates a StatusMentionMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

StatusMentionMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:42858](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42858)

Gets the default type url for StatusMentionMessage

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

Defined in: [WAProto/index.d.ts:42845](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42845)

Creates a plain object from a StatusMentionMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`StatusMentionMessage`](StatusMentionMessage.md)

StatusMentionMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:42830](https://github.com/Fokusdotid/bail/blob/546bbbb35e652e95f45982a71bee62b2c682e4eb/WAProto/index.d.ts#L42830)

Verifies a StatusMentionMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
