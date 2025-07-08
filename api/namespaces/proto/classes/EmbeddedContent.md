# Class: EmbeddedContent

Defined in: [WAProto/index.d.ts:13778](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13778)

Represents an EmbeddedContent.

## Implements

- [`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

## Constructors

### new EmbeddedContent()

> **new EmbeddedContent**(`properties`?): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:13784](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13784)

Constructs a new EmbeddedContent.

#### Parameters

##### properties?

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

Properties to set

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

## Properties

### content?

> `optional` **content**: `"embeddedMessage"` \| `"embeddedMusic"`

Defined in: [WAProto/index.d.ts:13793](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13793)

EmbeddedContent content.

***

### embeddedMessage?

> `optional` **embeddedMessage**: `null` \| [`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:13787](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13787)

EmbeddedContent embeddedMessage.

#### Implementation of

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md).[`embeddedMessage`](../interfaces/IEmbeddedContent.md#embeddedmessage)

***

### embeddedMusic?

> `optional` **embeddedMusic**: `null` \| [`IEmbeddedMusic`](../interfaces/IEmbeddedMusic.md)

Defined in: [WAProto/index.d.ts:13790](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13790)

EmbeddedContent embeddedMusic.

#### Implementation of

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md).[`embeddedMusic`](../interfaces/IEmbeddedContent.md#embeddedmusic)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13863](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13863)

Converts this EmbeddedContent to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:13800](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13800)

Creates a new EmbeddedContent instance using the specified properties.

#### Parameters

##### properties?

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

Properties to set

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

EmbeddedContent instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:13826](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13826)

Decodes an EmbeddedContent message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

EmbeddedContent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:13835](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13835)

Decodes an EmbeddedContent message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

EmbeddedContent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13808](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13808)

Encodes the specified EmbeddedContent message. Does not implicitly [verify](EmbeddedContent.md#verify) messages.

#### Parameters

##### message

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

EmbeddedContent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:13816](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13816)

Encodes the specified EmbeddedContent message, length delimited. Does not implicitly [verify](EmbeddedContent.md#verify) messages.

#### Parameters

##### message

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

EmbeddedContent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:13849](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13849)

Creates an EmbeddedContent message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

EmbeddedContent

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13870](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13870)

Gets the default type url for EmbeddedContent

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

Defined in: [WAProto/index.d.ts:13857](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13857)

Creates a plain object from an EmbeddedContent message. Also converts values to other types if specified.

#### Parameters

##### message

[`EmbeddedContent`](EmbeddedContent.md)

EmbeddedContent

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:13842](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L13842)

Verifies an EmbeddedContent message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
