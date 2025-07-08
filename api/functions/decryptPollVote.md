# Function: decryptPollVote()

> **decryptPollVote**(`vote`, `ctx`): [`PollVoteMessage`](../namespaces/proto/namespaces/Message/classes/PollVoteMessage.md)

Defined in: [src/Utils/process-message.ts:122](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/src/Utils/process-message.ts#L122)

Decrypt a poll vote

## Parameters

### vote

[`IPollEncValue`](../namespaces/proto/namespaces/Message/interfaces/IPollEncValue.md)

encrypted vote

### ctx

`PollContext`

additional info about the poll required for decryption

## Returns

[`PollVoteMessage`](../namespaces/proto/namespaces/Message/classes/PollVoteMessage.md)

list of SHA256 options
