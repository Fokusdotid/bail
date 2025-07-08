# Class: BotReminderMetadata

Defined in: [WAProto/index.d.ts:6702](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6702)

Represents a BotReminderMetadata.

## Implements

- [`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

## Constructors

### new BotReminderMetadata()

> **new BotReminderMetadata**(`properties`?): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:6708](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6708)

Constructs a new BotReminderMetadata.

#### Parameters

##### properties?

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

Properties to set

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

## Properties

### action?

> `optional` **action**: `null` \| [`ReminderAction`](../namespaces/BotReminderMetadata/enumerations/ReminderAction.md)

Defined in: [WAProto/index.d.ts:6714](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6714)

BotReminderMetadata action.

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`action`](../interfaces/IBotReminderMetadata.md#action)

***

### frequency?

> `optional` **frequency**: `null` \| [`ReminderFrequency`](../namespaces/BotReminderMetadata/enumerations/ReminderFrequency.md)

Defined in: [WAProto/index.d.ts:6723](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6723)

BotReminderMetadata frequency.

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`frequency`](../interfaces/IBotReminderMetadata.md#frequency)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6717](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6717)

BotReminderMetadata name.

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`name`](../interfaces/IBotReminderMetadata.md#name)

***

### nextTriggerTimestamp?

> `optional` **nextTriggerTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6720](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6720)

BotReminderMetadata nextTriggerTimestamp.

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`nextTriggerTimestamp`](../interfaces/IBotReminderMetadata.md#nexttriggertimestamp)

***

### requestMessageKey?

> `optional` **requestMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:6711](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6711)

BotReminderMetadata requestMessageKey.

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`requestMessageKey`](../interfaces/IBotReminderMetadata.md#requestmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6793](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6793)

Converts this BotReminderMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:6730](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6730)

Creates a new BotReminderMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

Properties to set

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

BotReminderMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:6756](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6756)

Decodes a BotReminderMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

BotReminderMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:6765](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6765)

Decodes a BotReminderMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

BotReminderMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6738](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6738)

Encodes the specified BotReminderMetadata message. Does not implicitly [verify](BotReminderMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

BotReminderMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:6746](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6746)

Encodes the specified BotReminderMetadata message, length delimited. Does not implicitly [verify](BotReminderMetadata.md#verify) messages.

#### Parameters

##### message

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

BotReminderMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:6779](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6779)

Creates a BotReminderMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

BotReminderMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6800](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6800)

Gets the default type url for BotReminderMetadata

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

Defined in: [WAProto/index.d.ts:6787](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6787)

Creates a plain object from a BotReminderMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`BotReminderMetadata`](BotReminderMetadata.md)

BotReminderMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:6772](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L6772)

Verifies a BotReminderMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
