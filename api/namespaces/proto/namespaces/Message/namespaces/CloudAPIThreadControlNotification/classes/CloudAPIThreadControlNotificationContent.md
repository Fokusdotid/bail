# Class: CloudAPIThreadControlNotificationContent

Defined in: [WAProto/index.d.ts:21590](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21590)

Represents a CloudAPIThreadControlNotificationContent.

## Implements

- [`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

## Constructors

### new CloudAPIThreadControlNotificationContent()

> **new CloudAPIThreadControlNotificationContent**(`properties`?): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:21596](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21596)

Constructs a new CloudAPIThreadControlNotificationContent.

#### Parameters

##### properties?

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

Properties to set

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

## Properties

### extraJson?

> `optional` **extraJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21602](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21602)

CloudAPIThreadControlNotificationContent extraJson.

#### Implementation of

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md).[`extraJson`](../interfaces/ICloudAPIThreadControlNotificationContent.md#extrajson)

***

### handoffNotificationText?

> `optional` **handoffNotificationText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:21599](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21599)

CloudAPIThreadControlNotificationContent handoffNotificationText.

#### Implementation of

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md).[`handoffNotificationText`](../interfaces/ICloudAPIThreadControlNotificationContent.md#handoffnotificationtext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:21672](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21672)

Converts this CloudAPIThreadControlNotificationContent to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:21609](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21609)

Creates a new CloudAPIThreadControlNotificationContent instance using the specified properties.

#### Parameters

##### properties?

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

Properties to set

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

CloudAPIThreadControlNotificationContent instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:21635](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21635)

Decodes a CloudAPIThreadControlNotificationContent message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

CloudAPIThreadControlNotificationContent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:21644](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21644)

Decodes a CloudAPIThreadControlNotificationContent message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

CloudAPIThreadControlNotificationContent

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21617](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21617)

Encodes the specified CloudAPIThreadControlNotificationContent message. Does not implicitly [verify](CloudAPIThreadControlNotificationContent.md#verify) messages.

#### Parameters

##### message

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

CloudAPIThreadControlNotificationContent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:21625](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21625)

Encodes the specified CloudAPIThreadControlNotificationContent message, length delimited. Does not implicitly [verify](CloudAPIThreadControlNotificationContent.md#verify) messages.

#### Parameters

##### message

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

CloudAPIThreadControlNotificationContent message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:21658](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21658)

Creates a CloudAPIThreadControlNotificationContent message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

CloudAPIThreadControlNotificationContent

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:21679](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21679)

Gets the default type url for CloudAPIThreadControlNotificationContent

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

Defined in: [WAProto/index.d.ts:21666](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21666)

Creates a plain object from a CloudAPIThreadControlNotificationContent message. Also converts values to other types if specified.

#### Parameters

##### message

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

CloudAPIThreadControlNotificationContent

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:21651](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/WAProto/index.d.ts#L21651)

Verifies a CloudAPIThreadControlNotificationContent message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
