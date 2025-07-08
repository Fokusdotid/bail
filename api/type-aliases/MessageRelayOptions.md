# Type Alias: MessageRelayOptions

> **MessageRelayOptions**: `MinimalRelayOptions` & `object`

Defined in: [src/Types/Message.ts:240](https://github.com/Fokusdotid/bail/blob/a029a4f9908cd3806112e8438f5a31dda1376b84/src/Types/Message.ts#L240)

## Type declaration

### additionalAttributes?

> `optional` **additionalAttributes**: `object`

additional attributes to add to the WA binary node

#### Index Signature

\[`_`: `string`\]: `string`

### additionalNodes?

> `optional` **additionalNodes**: [`BinaryNode`](BinaryNode.md)[]

### participant?

> `optional` **participant**: `object`

only send to a specific participant; used when a message decryption fails for a single user

#### participant.count

> **count**: `number`

#### participant.jid

> **jid**: `string`

### statusJidList?

> `optional` **statusJidList**: `string`[]

jid list of participants for status@broadcast

### useUserDevicesCache?

> `optional` **useUserDevicesCache**: `boolean`

should we use the devices cache, or fetch afresh from the server; default assumed to be "true"
