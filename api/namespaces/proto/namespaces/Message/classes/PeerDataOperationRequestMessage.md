# Class: PeerDataOperationRequestMessage

Defined in: [WAProto/index.d.ts:29271](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29271)

Represents a PeerDataOperationRequestMessage.

## Implements

- [`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

## Constructors

### new PeerDataOperationRequestMessage()

> **new PeerDataOperationRequestMessage**(`properties`?): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:29277](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29277)

Constructs a new PeerDataOperationRequestMessage.

#### Parameters

##### properties?

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

## Properties

### fullHistorySyncOnDemandRequest?

> `optional` **fullHistorySyncOnDemandRequest**: `null` \| [`IFullHistorySyncOnDemandRequest`](../namespaces/PeerDataOperationRequestMessage/interfaces/IFullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29295](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29295)

PeerDataOperationRequestMessage fullHistorySyncOnDemandRequest.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`fullHistorySyncOnDemandRequest`](../interfaces/IPeerDataOperationRequestMessage.md#fullhistorysyncondemandrequest)

***

### historySyncOnDemandRequest?

> `optional` **historySyncOnDemandRequest**: `null` \| [`IHistorySyncOnDemandRequest`](../namespaces/PeerDataOperationRequestMessage/interfaces/IHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:29289](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29289)

PeerDataOperationRequestMessage historySyncOnDemandRequest.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`historySyncOnDemandRequest`](../interfaces/IPeerDataOperationRequestMessage.md#historysyncondemandrequest)

***

### peerDataOperationRequestType?

> `optional` **peerDataOperationRequestType**: `null` \| [`PeerDataOperationRequestType`](../enumerations/PeerDataOperationRequestType.md)

Defined in: [WAProto/index.d.ts:29280](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29280)

PeerDataOperationRequestMessage peerDataOperationRequestType.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`peerDataOperationRequestType`](../interfaces/IPeerDataOperationRequestMessage.md#peerdataoperationrequesttype)

***

### placeholderMessageResendRequest

> **placeholderMessageResendRequest**: [`IPlaceholderMessageResendRequest`](../namespaces/PeerDataOperationRequestMessage/interfaces/IPlaceholderMessageResendRequest.md)[]

Defined in: [WAProto/index.d.ts:29292](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29292)

PeerDataOperationRequestMessage placeholderMessageResendRequest.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`placeholderMessageResendRequest`](../interfaces/IPeerDataOperationRequestMessage.md#placeholdermessageresendrequest)

***

### requestStickerReupload

> **requestStickerReupload**: [`IRequestStickerReupload`](../namespaces/PeerDataOperationRequestMessage/interfaces/IRequestStickerReupload.md)[]

Defined in: [WAProto/index.d.ts:29283](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29283)

PeerDataOperationRequestMessage requestStickerReupload.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`requestStickerReupload`](../interfaces/IPeerDataOperationRequestMessage.md#requeststickerreupload)

***

### requestUrlPreview

> **requestUrlPreview**: [`IRequestUrlPreview`](../namespaces/PeerDataOperationRequestMessage/interfaces/IRequestUrlPreview.md)[]

Defined in: [WAProto/index.d.ts:29286](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29286)

PeerDataOperationRequestMessage requestUrlPreview.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`requestUrlPreview`](../interfaces/IPeerDataOperationRequestMessage.md#requesturlpreview)

***

### syncdCollectionFatalRecoveryRequest?

> `optional` **syncdCollectionFatalRecoveryRequest**: `null` \| [`ISyncDCollectionFatalRecoveryRequest`](../namespaces/PeerDataOperationRequestMessage/interfaces/ISyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:29298](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29298)

PeerDataOperationRequestMessage syncdCollectionFatalRecoveryRequest.

#### Implementation of

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md).[`syncdCollectionFatalRecoveryRequest`](../interfaces/IPeerDataOperationRequestMessage.md#syncdcollectionfatalrecoveryrequest)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:29368](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29368)

Converts this PeerDataOperationRequestMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:29305](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29305)

Creates a new PeerDataOperationRequestMessage instance using the specified properties.

#### Parameters

##### properties?

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

Properties to set

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:29331](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29331)

Decodes a PeerDataOperationRequestMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:29340](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29340)

Decodes a PeerDataOperationRequestMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29313](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29313)

Encodes the specified PeerDataOperationRequestMessage message. Does not implicitly [verify](PeerDataOperationRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:29321](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29321)

Encodes the specified PeerDataOperationRequestMessage message, length delimited. Does not implicitly [verify](PeerDataOperationRequestMessage.md#verify) messages.

#### Parameters

##### message

[`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:29354](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29354)

Creates a PeerDataOperationRequestMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:29375](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29375)

Gets the default type url for PeerDataOperationRequestMessage

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

Defined in: [WAProto/index.d.ts:29362](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29362)

Creates a plain object from a PeerDataOperationRequestMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`PeerDataOperationRequestMessage`](PeerDataOperationRequestMessage.md)

PeerDataOperationRequestMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:29347](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L29347)

Verifies a PeerDataOperationRequestMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
