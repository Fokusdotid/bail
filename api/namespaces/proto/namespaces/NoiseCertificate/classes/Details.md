# Class: Details

Defined in: [WAProto/index.d.ts:37458](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37458)

Represents a Details.

## Implements

- [`IDetails`](../interfaces/IDetails.md)

## Constructors

### new Details()

> **new Details**(`properties`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:37464](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37464)

Constructs a new Details.

#### Parameters

##### properties?

[`IDetails`](../interfaces/IDetails.md)

Properties to set

#### Returns

[`Details`](Details.md)

## Properties

### expires?

> `optional` **expires**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:37473](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37473)

Details expires.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`expires`](../interfaces/IDetails.md#expires)

***

### issuer?

> `optional` **issuer**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37470](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37470)

Details issuer.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`issuer`](../interfaces/IDetails.md#issuer)

***

### key?

> `optional` **key**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:37479](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37479)

Details key.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`key`](../interfaces/IDetails.md#key)

***

### serial?

> `optional` **serial**: `null` \| `number`

Defined in: [WAProto/index.d.ts:37467](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37467)

Details serial.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`serial`](../interfaces/IDetails.md#serial)

***

### subject?

> `optional` **subject**: `null` \| `string`

Defined in: [WAProto/index.d.ts:37476](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37476)

Details subject.

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`subject`](../interfaces/IDetails.md#subject)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:37549](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37549)

Converts this Details to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:37486](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37486)

Creates a new Details instance using the specified properties.

#### Parameters

##### properties?

[`IDetails`](../interfaces/IDetails.md)

Properties to set

#### Returns

[`Details`](Details.md)

Details instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:37512](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37512)

Decodes a Details message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`Details`](Details.md)

Details

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:37521](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37521)

Decodes a Details message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`Details`](Details.md)

Details

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37494](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37494)

Encodes the specified Details message. Does not implicitly [verify](Details.md#verify) messages.

#### Parameters

##### message

[`IDetails`](../interfaces/IDetails.md)

Details message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:37502](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37502)

Encodes the specified Details message, length delimited. Does not implicitly [verify](Details.md#verify) messages.

#### Parameters

##### message

[`IDetails`](../interfaces/IDetails.md)

Details message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:37535](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37535)

Creates a Details message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`Details`](Details.md)

Details

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:37556](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37556)

Gets the default type url for Details

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

Defined in: [WAProto/index.d.ts:37543](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37543)

Creates a plain object from a Details message. Also converts values to other types if specified.

#### Parameters

##### message

[`Details`](Details.md)

Details

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:37528](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/WAProto/index.d.ts#L37528)

Verifies a Details message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
