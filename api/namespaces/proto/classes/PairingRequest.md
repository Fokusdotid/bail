# Class: PairingRequest

Defined in: [WAProto/index.d.ts:37816](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37816)

Represents a PairingRequest.

## Implements

- [`IPairingRequest`](../interfaces/IPairingRequest.md)

## Constructors

### new PairingRequest()

> **new PairingRequest**(`properties`?): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:37822](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37822)

Constructs a new PairingRequest.

#### Parameters

##### properties?

[`IPairingRequest`](../interfaces/IPairingRequest.md)

Properties to set

#### Returns

[`PairingRequest`](PairingRequest.md)

## Properties

### advSecret?

> `optional` **advSecret**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:37831](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37831)

PairingRequest advSecret.

#### Implementation of

[`IPairingRequest`](../interfaces/IPairingRequest.md).[`advSecret`](../interfaces/IPairingRequest.md#advsecret)

***

### companionIdentityKey?

> `optional` **companionIdentityKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:37828](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37828)

PairingRequest companionIdentityKey.

#### Implementation of

[`IPairingRequest`](../interfaces/IPairingRequest.md).[`companionIdentityKey`](../interfaces/IPairingRequest.md#companionidentitykey)

***

### companionPublicKey?

> `optional` **companionPublicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:37825](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37825)

PairingRequest companionPublicKey.

#### Implementation of

[`IPairingRequest`](../interfaces/IPairingRequest.md).[`companionPublicKey`](../interfaces/IPairingRequest.md#companionpublickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37901](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37901)

Converts this PairingRequest to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:37838](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37838)

Creates a new PairingRequest instance using the specified properties.

#### Parameters

##### properties?

[`IPairingRequest`](../interfaces/IPairingRequest.md)

Properties to set

#### Returns

[`PairingRequest`](PairingRequest.md)

PairingRequest instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:37864](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37864)

Decodes a PairingRequest message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PairingRequest`](PairingRequest.md)

PairingRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:37873](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37873)

Decodes a PairingRequest message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PairingRequest`](PairingRequest.md)

PairingRequest

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37846](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37846)

Encodes the specified PairingRequest message. Does not implicitly [verify](PairingRequest.md#verify) messages.

#### Parameters

##### message

[`IPairingRequest`](../interfaces/IPairingRequest.md)

PairingRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37854](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37854)

Encodes the specified PairingRequest message, length delimited. Does not implicitly [verify](PairingRequest.md#verify) messages.

#### Parameters

##### message

[`IPairingRequest`](../interfaces/IPairingRequest.md)

PairingRequest message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:37887](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37887)

Creates a PairingRequest message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PairingRequest`](PairingRequest.md)

PairingRequest

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:37908](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37908)

Gets the default type url for PairingRequest

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

Defined in: [WAProto/index.d.ts:37895](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37895)

Creates a plain object from a PairingRequest message. Also converts values to other types if specified.

#### Parameters

##### message

[`PairingRequest`](PairingRequest.md)

PairingRequest

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:37880](https://github.com/Fokusdotid/bail/blob/dad8cbc7bd41e0c17126095b0fc017b92c3d85cf/WAProto/index.d.ts#L37880)

Verifies a PairingRequest message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
