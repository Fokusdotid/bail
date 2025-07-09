# Class: GroupMention

Defined in: [WAProto/index.d.ts:15124](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15124)

Represents a GroupMention.

## Implements

- [`IGroupMention`](../interfaces/IGroupMention.md)

## Constructors

### new GroupMention()

> **new GroupMention**(`properties`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:15130](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15130)

Constructs a new GroupMention.

#### Parameters

##### properties?

[`IGroupMention`](../interfaces/IGroupMention.md)

Properties to set

#### Returns

[`GroupMention`](GroupMention.md)

## Properties

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:15133](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15133)

GroupMention groupJid.

#### Implementation of

[`IGroupMention`](../interfaces/IGroupMention.md).[`groupJid`](../interfaces/IGroupMention.md#groupjid)

***

### groupSubject?

> `optional` **groupSubject**: `null` \| `string`

Defined in: [WAProto/index.d.ts:15136](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15136)

GroupMention groupSubject.

#### Implementation of

[`IGroupMention`](../interfaces/IGroupMention.md).[`groupSubject`](../interfaces/IGroupMention.md#groupsubject)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:15206](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15206)

Converts this GroupMention to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:15143](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15143)

Creates a new GroupMention instance using the specified properties.

#### Parameters

##### properties?

[`IGroupMention`](../interfaces/IGroupMention.md)

Properties to set

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:15169](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15169)

Decodes a GroupMention message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:15178](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15178)

Decodes a GroupMention message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15151](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15151)

Encodes the specified GroupMention message. Does not implicitly [verify](GroupMention.md#verify) messages.

#### Parameters

##### message

[`IGroupMention`](../interfaces/IGroupMention.md)

GroupMention message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:15159](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15159)

Encodes the specified GroupMention message, length delimited. Does not implicitly [verify](GroupMention.md#verify) messages.

#### Parameters

##### message

[`IGroupMention`](../interfaces/IGroupMention.md)

GroupMention message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:15192](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15192)

Creates a GroupMention message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`GroupMention`](GroupMention.md)

GroupMention

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:15213](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15213)

Gets the default type url for GroupMention

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

Defined in: [WAProto/index.d.ts:15200](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15200)

Creates a plain object from a GroupMention message. Also converts values to other types if specified.

#### Parameters

##### message

[`GroupMention`](GroupMention.md)

GroupMention

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:15185](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L15185)

Verifies a GroupMention message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
