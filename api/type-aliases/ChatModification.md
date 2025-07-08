# Type Alias: ChatModification

> **ChatModification**: \{ `archive`: `boolean`; `lastMessages`: [`LastMessageList`](LastMessageList.md); \} \| \{ `pushNameSetting`: `string`; \} \| \{ `pin`: `boolean`; \} \| \{ `mute`: `number` \| `null`; \} \| \{ `clear`: `boolean`; `lastMessages`: [`LastMessageList`](LastMessageList.md); \} \| \{ `deleteForMe`: \{ `deleteMedia`: `boolean`; `key`: [`WAMessageKey`](WAMessageKey.md); `timestamp`: `number`; \}; \} \| \{ `star`: \{ `messages`: `object`[]; `star`: `boolean`; \}; \} \| \{ `lastMessages`: [`LastMessageList`](LastMessageList.md); `markRead`: `boolean`; \} \| \{ `delete`: `true`; `lastMessages`: [`LastMessageList`](LastMessageList.md); \} \| \{ `addLabel`: `LabelActionBody`; \} \| \{ `addChatLabel`: `ChatLabelAssociationActionBody`; \} \| \{ `removeChatLabel`: `ChatLabelAssociationActionBody`; \} \| \{ `addMessageLabel`: `MessageLabelAssociationActionBody`; \} \| \{ `removeMessageLabel`: `MessageLabelAssociationActionBody`; \}

Defined in: [src/Types/Chat.ts:84](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/src/Types/Chat.ts#L84)

## Type declaration

\{ `archive`: `boolean`; `lastMessages`: [`LastMessageList`](LastMessageList.md); \}

### archive

> **archive**: `boolean`

### lastMessages

> **lastMessages**: [`LastMessageList`](LastMessageList.md)

\{ `pushNameSetting`: `string`; \}

### pushNameSetting

> **pushNameSetting**: `string`

\{ `pin`: `boolean`; \}

### pin

> **pin**: `boolean`

\{ `mute`: `number` \| `null`; \}

### mute

> **mute**: `number` \| `null`

mute for duration, or provide timestamp of mute to remove

\{ `clear`: `boolean`; `lastMessages`: [`LastMessageList`](LastMessageList.md); \}

### clear

> **clear**: `boolean`

### lastMessages

> **lastMessages**: [`LastMessageList`](LastMessageList.md)

\{ `deleteForMe`: \{ `deleteMedia`: `boolean`; `key`: [`WAMessageKey`](WAMessageKey.md); `timestamp`: `number`; \}; \}

### deleteForMe

> **deleteForMe**: `object`

#### deleteForMe.deleteMedia

> **deleteMedia**: `boolean`

#### deleteForMe.key

> **key**: [`WAMessageKey`](WAMessageKey.md)

#### deleteForMe.timestamp

> **timestamp**: `number`

\{ `star`: \{ `messages`: `object`[]; `star`: `boolean`; \}; \}

### star

> **star**: `object`

#### star.messages

> **messages**: `object`[]

#### star.star

> **star**: `boolean`

\{ `lastMessages`: [`LastMessageList`](LastMessageList.md); `markRead`: `boolean`; \}

### lastMessages

> **lastMessages**: [`LastMessageList`](LastMessageList.md)

### markRead

> **markRead**: `boolean`

\{ `delete`: `true`; `lastMessages`: [`LastMessageList`](LastMessageList.md); \}

### delete

> **delete**: `true`

### lastMessages

> **lastMessages**: [`LastMessageList`](LastMessageList.md)

\{ `addLabel`: `LabelActionBody`; \}

### addLabel

> **addLabel**: `LabelActionBody`

\{ `addChatLabel`: `ChatLabelAssociationActionBody`; \}

### addChatLabel

> **addChatLabel**: `ChatLabelAssociationActionBody`

\{ `removeChatLabel`: `ChatLabelAssociationActionBody`; \}

### removeChatLabel

> **removeChatLabel**: `ChatLabelAssociationActionBody`

\{ `addMessageLabel`: `MessageLabelAssociationActionBody`; \}

### addMessageLabel

> **addMessageLabel**: `MessageLabelAssociationActionBody`

\{ `removeMessageLabel`: `MessageLabelAssociationActionBody`; \}

### removeMessageLabel

> **removeMessageLabel**: `MessageLabelAssociationActionBody`
