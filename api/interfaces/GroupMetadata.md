# Interface: GroupMetadata

Defined in: [src/Types/GroupMetadata.ts:15](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L15)

## Properties

### addressingMode

> **addressingMode**: `"pn"` \| `"lid"`

Defined in: [src/Types/GroupMetadata.ts:18](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L18)

group uses 'lid' or 'pn' to send messages

***

### announce?

> `optional` **announce**: `boolean`

Defined in: [src/Types/GroupMetadata.ts:39](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L39)

is set when the group only allows admins to write messages

***

### author?

> `optional` **author**: `string`

Defined in: [src/Types/GroupMetadata.ts:55](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L55)

the person who added you to group or changed some setting in group

***

### creation?

> `optional` **creation**: `number`

Defined in: [src/Types/GroupMetadata.ts:28](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L28)

***

### desc?

> `optional` **desc**: `string`

Defined in: [src/Types/GroupMetadata.ts:29](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L29)

***

### descId?

> `optional` **descId**: `string`

Defined in: [src/Types/GroupMetadata.ts:32](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L32)

***

### descOwner?

> `optional` **descOwner**: `string`

Defined in: [src/Types/GroupMetadata.ts:30](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L30)

***

### descOwnerJid?

> `optional` **descOwnerJid**: `string`

Defined in: [src/Types/GroupMetadata.ts:31](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L31)

***

### descTime?

> `optional` **descTime**: `number`

Defined in: [src/Types/GroupMetadata.ts:33](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L33)

***

### ephemeralDuration?

> `optional` **ephemeralDuration**: `number`

Defined in: [src/Types/GroupMetadata.ts:52](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L52)

***

### id

> **id**: `string`

Defined in: [src/Types/GroupMetadata.ts:16](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L16)

***

### inviteCode?

> `optional` **inviteCode**: `string`

Defined in: [src/Types/GroupMetadata.ts:53](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L53)

***

### isCommunity?

> `optional` **isCommunity**: `boolean`

Defined in: [src/Types/GroupMetadata.ts:45](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L45)

is this a community

***

### isCommunityAnnounce?

> `optional` **isCommunityAnnounce**: `boolean`

Defined in: [src/Types/GroupMetadata.ts:47](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L47)

is this the announce of a community

***

### joinApprovalMode?

> `optional` **joinApprovalMode**: `boolean`

Defined in: [src/Types/GroupMetadata.ts:43](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L43)

Request approval to join the group

***

### linkedParent?

> `optional` **linkedParent**: `string`

Defined in: [src/Types/GroupMetadata.ts:35](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L35)

if this group is part of a community, it returns the jid of the community to which it belongs

***

### memberAddMode?

> `optional` **memberAddMode**: `boolean`

Defined in: [src/Types/GroupMetadata.ts:41](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L41)

is set when the group also allows members to add participants

***

### owner

> **owner**: `undefined` \| `string`

Defined in: [src/Types/GroupMetadata.ts:19](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L19)

***

### owner\_country\_code

> **owner\_country\_code**: `string`

Defined in: [src/Types/GroupMetadata.ts:21](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L21)

***

### ownerJid?

> `optional` **ownerJid**: `string`

Defined in: [src/Types/GroupMetadata.ts:20](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L20)

***

### participants

> **participants**: [`GroupParticipant`](../type-aliases/GroupParticipant.md)[]

Defined in: [src/Types/GroupMetadata.ts:51](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L51)

***

### restrict?

> `optional` **restrict**: `boolean`

Defined in: [src/Types/GroupMetadata.ts:37](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L37)

is set when the group only allows admins to change group settings

***

### size?

> `optional` **size**: `number`

Defined in: [src/Types/GroupMetadata.ts:49](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L49)

number of group participants

***

### subject

> **subject**: `string`

Defined in: [src/Types/GroupMetadata.ts:22](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L22)

***

### subjectOwner?

> `optional` **subjectOwner**: `string`

Defined in: [src/Types/GroupMetadata.ts:24](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L24)

group subject owner

***

### subjectOwnerJid?

> `optional` **subjectOwnerJid**: `string`

Defined in: [src/Types/GroupMetadata.ts:25](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L25)

***

### subjectTime?

> `optional` **subjectTime**: `number`

Defined in: [src/Types/GroupMetadata.ts:27](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Types/GroupMetadata.ts#L27)

group subject modification date
