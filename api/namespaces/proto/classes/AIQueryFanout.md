# Class: AIQueryFanout

Defined in: [WAProto/index.d.ts:601](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L601)

Represents a AIQueryFanout.

## Implements

- [`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

## Constructors

### new AIQueryFanout()

> **new AIQueryFanout**(`properties`?): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:607](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L607)

Constructs a new AIQueryFanout.

#### Parameters

##### properties?

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

Properties to set

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:613](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L613)

AIQueryFanout message.

#### Implementation of

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md).[`message`](../interfaces/IAIQueryFanout.md#message)

***

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:610](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L610)

AIQueryFanout messageKey.

#### Implementation of

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md).[`messageKey`](../interfaces/IAIQueryFanout.md#messagekey)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:616](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L616)

AIQueryFanout timestamp.

#### Implementation of

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md).[`timestamp`](../interfaces/IAIQueryFanout.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:686](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L686)

Converts this AIQueryFanout to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:623](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L623)

Creates a new AIQueryFanout instance using the specified properties.

#### Parameters

##### properties?

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

Properties to set

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

AIQueryFanout instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:649](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L649)

Decodes a AIQueryFanout message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

AIQueryFanout

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:658](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L658)

Decodes a AIQueryFanout message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

AIQueryFanout

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:631](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L631)

Encodes the specified AIQueryFanout message. Does not implicitly [verify](AIQueryFanout.md#verify) messages.

#### Parameters

##### message

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

AIQueryFanout message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:639](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L639)

Encodes the specified AIQueryFanout message, length delimited. Does not implicitly [verify](AIQueryFanout.md#verify) messages.

#### Parameters

##### message

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

AIQueryFanout message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:672](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L672)

Creates a AIQueryFanout message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

AIQueryFanout

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:693](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L693)

Gets the default type url for AIQueryFanout

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

Defined in: [WAProto/index.d.ts:680](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L680)

Creates a plain object from a AIQueryFanout message. Also converts values to other types if specified.

#### Parameters

##### message

[`AIQueryFanout`](AIQueryFanout.md)

AIQueryFanout

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:665](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L665)

Verifies a AIQueryFanout message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
