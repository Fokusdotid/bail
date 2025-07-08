# Class: ProtocolMessage

Defined in: [WAProto/index.d.ts:32643](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32643)

Represents a ProtocolMessage.

## Implements

- [`IProtocolMessage`](../interfaces/IProtocolMessage.md)

## Constructors

### new ProtocolMessage()

> **new ProtocolMessage**(`properties`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:32649](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32649)

Constructs a new ProtocolMessage.

#### Parameters

##### properties?

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

Properties to set

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

## Properties

### aiPsiMetadata?

> `optional` **aiPsiMetadata**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:32715](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32715)

ProtocolMessage aiPsiMetadata.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`aiPsiMetadata`](../interfaces/IProtocolMessage.md#aipsimetadata)

***

### aiQueryFanout?

> `optional` **aiQueryFanout**: `null` \| [`IAIQueryFanout`](../../../interfaces/IAIQueryFanout.md)

Defined in: [WAProto/index.d.ts:32718](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32718)

ProtocolMessage aiQueryFanout.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`aiQueryFanout`](../interfaces/IProtocolMessage.md#aiqueryfanout)

***

### appStateFatalExceptionNotification?

> `optional` **appStateFatalExceptionNotification**: `null` \| [`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:32676](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32676)

ProtocolMessage appStateFatalExceptionNotification.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateFatalExceptionNotification`](../interfaces/IProtocolMessage.md#appstatefatalexceptionnotification)

***

### appStateSyncKeyRequest?

> `optional` **appStateSyncKeyRequest**: `null` \| [`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:32670](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32670)

ProtocolMessage appStateSyncKeyRequest.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateSyncKeyRequest`](../interfaces/IProtocolMessage.md#appstatesynckeyrequest)

***

### appStateSyncKeyShare?

> `optional` **appStateSyncKeyShare**: `null` \| [`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:32667](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32667)

ProtocolMessage appStateSyncKeyShare.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateSyncKeyShare`](../interfaces/IProtocolMessage.md#appstatesynckeyshare)

***

### botFeedbackMessage?

> `optional` **botFeedbackMessage**: `null` \| [`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:32694](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32694)

ProtocolMessage botFeedbackMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`botFeedbackMessage`](../interfaces/IProtocolMessage.md#botfeedbackmessage)

***

### cloudApiThreadControlNotification?

> `optional` **cloudApiThreadControlNotification**: `null` \| [`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:32706](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32706)

ProtocolMessage cloudApiThreadControlNotification.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`cloudApiThreadControlNotification`](../interfaces/IProtocolMessage.md#cloudapithreadcontrolnotification)

***

### disappearingMode?

> `optional` **disappearingMode**: `null` \| [`IDisappearingMode`](../../../interfaces/IDisappearingMode.md)

Defined in: [WAProto/index.d.ts:32679](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32679)

ProtocolMessage disappearingMode.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`disappearingMode`](../interfaces/IProtocolMessage.md#disappearingmode)

***

### editedMessage?

> `optional` **editedMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:32682](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32682)

ProtocolMessage editedMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`editedMessage`](../interfaces/IProtocolMessage.md#editedmessage)

***

### ephemeralExpiration?

> `optional` **ephemeralExpiration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:32658](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32658)

ProtocolMessage ephemeralExpiration.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`ephemeralExpiration`](../interfaces/IProtocolMessage.md#ephemeralexpiration)

***

### ephemeralSettingTimestamp?

> `optional` **ephemeralSettingTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:32661](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32661)

ProtocolMessage ephemeralSettingTimestamp.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`ephemeralSettingTimestamp`](../interfaces/IProtocolMessage.md#ephemeralsettingtimestamp)

***

### historySyncNotification?

> `optional` **historySyncNotification**: `null` \| [`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md)

Defined in: [WAProto/index.d.ts:32664](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32664)

ProtocolMessage historySyncNotification.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`historySyncNotification`](../interfaces/IProtocolMessage.md#historysyncnotification)

***

### initialSecurityNotificationSettingSync?

> `optional` **initialSecurityNotificationSettingSync**: `null` \| [`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:32673](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32673)

ProtocolMessage initialSecurityNotificationSettingSync.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`initialSecurityNotificationSettingSync`](../interfaces/IProtocolMessage.md#initialsecuritynotificationsettingsync)

***

### invokerJid?

> `optional` **invokerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:32697](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32697)

ProtocolMessage invokerJid.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`invokerJid`](../interfaces/IProtocolMessage.md#invokerjid)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:32652](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32652)

ProtocolMessage key.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`key`](../interfaces/IProtocolMessage.md#key)

***

### lidMigrationMappingSyncMessage?

> `optional` **lidMigrationMappingSyncMessage**: `null` \| [`ILIDMigrationMappingSyncMessage`](../../../interfaces/ILIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:32709](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32709)

ProtocolMessage lidMigrationMappingSyncMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`lidMigrationMappingSyncMessage`](../interfaces/IProtocolMessage.md#lidmigrationmappingsyncmessage)

***

### limitSharing?

> `optional` **limitSharing**: `null` \| [`ILimitSharing`](../../../interfaces/ILimitSharing.md)

Defined in: [WAProto/index.d.ts:32712](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32712)

ProtocolMessage limitSharing.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`limitSharing`](../interfaces/IProtocolMessage.md#limitsharing)

***

### mediaNotifyMessage?

> `optional` **mediaNotifyMessage**: `null` \| [`IMediaNotifyMessage`](../../../interfaces/IMediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:32703](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32703)

ProtocolMessage mediaNotifyMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`mediaNotifyMessage`](../interfaces/IProtocolMessage.md#medianotifymessage)

***

### memberLabel?

> `optional` **memberLabel**: `null` \| [`IMemberLabel`](../../../interfaces/IMemberLabel.md)

Defined in: [WAProto/index.d.ts:32721](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32721)

ProtocolMessage memberLabel.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`memberLabel`](../interfaces/IProtocolMessage.md#memberlabel)

***

### peerDataOperationRequestMessage?

> `optional` **peerDataOperationRequestMessage**: `null` \| [`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:32688](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32688)

ProtocolMessage peerDataOperationRequestMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`peerDataOperationRequestMessage`](../interfaces/IProtocolMessage.md#peerdataoperationrequestmessage)

***

### peerDataOperationRequestResponseMessage?

> `optional` **peerDataOperationRequestResponseMessage**: `null` \| [`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:32691](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32691)

ProtocolMessage peerDataOperationRequestResponseMessage.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`peerDataOperationRequestResponseMessage`](../interfaces/IProtocolMessage.md#peerdataoperationrequestresponsemessage)

***

### requestWelcomeMessageMetadata?

> `optional` **requestWelcomeMessageMetadata**: `null` \| [`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:32700](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32700)

ProtocolMessage requestWelcomeMessageMetadata.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`requestWelcomeMessageMetadata`](../interfaces/IProtocolMessage.md#requestwelcomemessagemetadata)

***

### timestampMs?

> `optional` **timestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:32685](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32685)

ProtocolMessage timestampMs.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`timestampMs`](../interfaces/IProtocolMessage.md#timestampms)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/ProtocolMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:32655](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32655)

ProtocolMessage type.

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`type`](../interfaces/IProtocolMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:32791](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32791)

Converts this ProtocolMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:32728](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32728)

Creates a new ProtocolMessage instance using the specified properties.

#### Parameters

##### properties?

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

Properties to set

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:32754](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32754)

Decodes a ProtocolMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:32763](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32763)

Decodes a ProtocolMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32736](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32736)

Encodes the specified ProtocolMessage message. Does not implicitly [verify](ProtocolMessage.md#verify) messages.

#### Parameters

##### message

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

ProtocolMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:32744](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32744)

Encodes the specified ProtocolMessage message, length delimited. Does not implicitly [verify](ProtocolMessage.md#verify) messages.

#### Parameters

##### message

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

ProtocolMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:32777](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32777)

Creates a ProtocolMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:32798](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32798)

Gets the default type url for ProtocolMessage

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

Defined in: [WAProto/index.d.ts:32785](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32785)

Creates a plain object from a ProtocolMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProtocolMessage`](ProtocolMessage.md)

ProtocolMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:32770](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/WAProto/index.d.ts#L32770)

Verifies a ProtocolMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
