# Type Alias: AnyMessageContent

> **AnyMessageContent**: [`AnyRegularMessageContent`](AnyRegularMessageContent.md) \| \{ `force`: `boolean`; `forward`: [`WAMessage`](WAMessage.md); \} \| \{ `delete`: [`WAMessageKey`](WAMessageKey.md); \} \| \{ `disappearingMessagesInChat`: `boolean` \| `number`; \}

Defined in: [src/Types/Message.ts:217](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/src/Types/Message.ts#L217)

## Type declaration

[`AnyRegularMessageContent`](AnyRegularMessageContent.md)

\{ `force`: `boolean`; `forward`: [`WAMessage`](WAMessage.md); \}

### force?

> `optional` **force**: `boolean`

### forward

> **forward**: [`WAMessage`](WAMessage.md)

\{ `delete`: [`WAMessageKey`](WAMessageKey.md); \}

### delete

> **delete**: [`WAMessageKey`](WAMessageKey.md)

Delete your message or anyone's message in a group (admin required)

\{ `disappearingMessagesInChat`: `boolean` \| `number`; \}

### disappearingMessagesInChat

> **disappearingMessagesInChat**: `boolean` \| `number`
