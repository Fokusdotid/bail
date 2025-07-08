# Function: getAggregateVotesInPollMessage()

> **getAggregateVotesInPollMessage**(`msg`, `meId`?): `VoteAggregation`[]

Defined in: [src/Utils/messages.ts:914](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Utils/messages.ts#L914)

Aggregates all poll updates in a poll.

## Parameters

### msg

`Pick`\<[`WAMessage`](../type-aliases/WAMessage.md), `"message"` \| `"pollUpdates"`\>

the poll creation message

### meId?

`string`

your jid

## Returns

`VoteAggregation`[]

A list of options & their voters
