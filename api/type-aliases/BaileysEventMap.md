# Type Alias: BaileysEventMap

> **BaileysEventMap**: `object`

Defined in: [src/Types/Events.ts:13](https://github.com/Fokusdotid/bail/blob/043003e0dc220c8f52aef36f90c7026f3a192427/src/Types/Events.ts#L13)

## Type declaration

#### blocklist.set

> **set**: `object`

#### blocklist.set.blocklist

> **blocklist**: `string`[]

#### blocklist.update

> **update**: `object`

#### blocklist.update.blocklist

> **blocklist**: `string`[]

#### blocklist.update.type

> **type**: `"add"` \| `"remove"`

### call

> **call**: [`WACallEvent`](WACallEvent.md)[]

Receive an update on a call, including when the call was received, rejected, accepted

#### chats.delete

> **delete**: `string`[]

delete chats with given ID

#### chats.phoneNumberShare

> **phoneNumberShare**: `object`

#### chats.phoneNumberShare.jid

> **jid**: `string`

#### chats.phoneNumberShare.lid

> **lid**: `string`

#### chats.update

> **update**: [`ChatUpdate`](ChatUpdate.md)[]

update the given chats

#### chats.upsert

> **upsert**: [`Chat`](Chat.md)[]

upsert chats

#### connection.update

> **update**: `Partial`\<[`ConnectionState`](ConnectionState.md)\>

connection state has been updated -- WS closed, opened, connecting etc.

#### contacts.update

> **update**: `Partial`\<[`Contact`](../interfaces/Contact.md)\>[]

#### contacts.upsert

> **upsert**: [`Contact`](../interfaces/Contact.md)[]

#### creds.update

> **update**: `Partial`\<[`AuthenticationCreds`](AuthenticationCreds.md)\>

credentials updated -- some metadata, keys or something

#### group-participants.update

> **update**: `object`

apply an action to participants in a group

#### group-participants.update.action

> **action**: [`ParticipantAction`](ParticipantAction.md)

#### group-participants.update.author

> **author**: `string`

#### group-participants.update.id

> **id**: `string`

#### group-participants.update.participants

> **participants**: `string`[]

#### group.join-request

> **join-request**: `object`

#### group.join-request.action

> **action**: [`RequestJoinAction`](RequestJoinAction.md)

#### group.join-request.author

> **author**: `string`

#### group.join-request.id

> **id**: `string`

#### group.join-request.method

> **method**: [`RequestJoinMethod`](RequestJoinMethod.md)

#### group.join-request.participant

> **participant**: `string`

#### groups.update

> **update**: `Partial`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>[]

#### groups.upsert

> **upsert**: [`GroupMetadata`](../interfaces/GroupMetadata.md)[]

#### labels.association

> **association**: `object`

#### labels.association.association

> **association**: `LabelAssociation`

#### labels.association.type

> **type**: `"add"` \| `"remove"`

#### labels.edit

> **edit**: `Label`

#### message-receipt.update

> **update**: [`MessageUserReceiptUpdate`](MessageUserReceiptUpdate.md)[]

#### messages.delete

> **delete**: \{ `keys`: [`WAMessageKey`](WAMessageKey.md)[]; \} \| \{ `all`: `true`; `jid`: `string`; \}

#### messages.media-update

> **media-update**: `object`[]

#### messages.reaction

> **reaction**: `object`[]

message was reacted to. If reaction was removed -- then "reaction.text" will be falsey

#### messages.update

> **update**: [`WAMessageUpdate`](WAMessageUpdate.md)[]

#### messages.upsert

> **upsert**: `object`

add/update the given messages. If they were received while the connection was online,
the update will have type: "notify"
if requestId is provided, then the messages was received from the phone due to it being unavailable

#### messages.upsert.messages

> **messages**: [`WAMessage`](WAMessage.md)[]

#### messages.upsert.requestId?

> `optional` **requestId**: `string`

#### messages.upsert.type

> **type**: [`MessageUpsertType`](MessageUpsertType.md)

#### messaging-history.set

> **set**: `object`

set chats (history sync), everything is reverse chronologically sorted

#### messaging-history.set.chats

> **chats**: [`Chat`](Chat.md)[]

#### messaging-history.set.contacts

> **contacts**: [`Contact`](../interfaces/Contact.md)[]

#### messaging-history.set.isLatest?

> `optional` **isLatest**: `boolean`

#### messaging-history.set.messages

> **messages**: [`WAMessage`](WAMessage.md)[]

#### messaging-history.set.peerDataRequestSessionId?

> `optional` **peerDataRequestSessionId**: `string` \| `null`

#### messaging-history.set.progress?

> `optional` **progress**: `number` \| `null`

#### messaging-history.set.syncType?

> `optional` **syncType**: [`HistorySyncType`](../namespaces/proto/namespaces/HistorySync/enumerations/HistorySyncType.md)

#### newsletter-participants.update

> **update**: `object`

#### newsletter-participants.update.action

> **action**: `string`

#### newsletter-participants.update.author

> **author**: `string`

#### newsletter-participants.update.id

> **id**: `string`

#### newsletter-participants.update.new\_role

> **new\_role**: `string`

#### newsletter-participants.update.user

> **user**: `string`

#### newsletter-settings.update

> **update**: `object`

#### newsletter-settings.update.id

> **id**: `string`

#### newsletter-settings.update.update

> **update**: `any`

#### newsletter.reaction

> **reaction**: `object`

Newsletter-related events

#### newsletter.reaction.id

> **id**: `string`

#### newsletter.reaction.reaction

> **reaction**: `object`

#### newsletter.reaction.reaction.code?

> `optional` **code**: `string`

#### newsletter.reaction.reaction.count?

> `optional` **count**: `number`

#### newsletter.reaction.reaction.removed?

> `optional` **removed**: `boolean`

#### newsletter.reaction.server\_id

> **server\_id**: `string`

#### newsletter.view

> **view**: `object`

#### newsletter.view.count

> **count**: `number`

#### newsletter.view.id

> **id**: `string`

#### newsletter.view.server\_id

> **server\_id**: `string`

#### presence.update

> **update**: `object`

presence of contact in a chat updated

#### presence.update.id

> **id**: `string`

#### presence.update.presences

> **presences**: `object`

##### Index Signature

\[`participant`: `string`\]: [`PresenceData`](../interfaces/PresenceData.md)
