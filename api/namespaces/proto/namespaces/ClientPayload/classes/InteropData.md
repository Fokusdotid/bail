# Class: InteropData

Defined in: [WAProto/index.d.ts:9561](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9561)

Represents an InteropData.

## Implements

- [`IInteropData`](../interfaces/IInteropData.md)

## Constructors

### new InteropData()

> **new InteropData**(`properties`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:9567](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9567)

Constructs a new InteropData.

#### Parameters

##### properties?

[`IInteropData`](../interfaces/IInteropData.md)

Properties to set

#### Returns

[`InteropData`](InteropData.md)

## Properties

### accountId?

> `optional` **accountId**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:9570](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9570)

InteropData accountId.

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`accountId`](../interfaces/IInteropData.md#accountid)

***

### enableReadReceipts?

> `optional` **enableReadReceipts**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:9576](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9576)

InteropData enableReadReceipts.

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`enableReadReceipts`](../interfaces/IInteropData.md#enablereadreceipts)

***

### token?

> `optional` **token**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:9573](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9573)

InteropData token.

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`token`](../interfaces/IInteropData.md#token)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9646](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9646)

Converts this InteropData to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:9583](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9583)

Creates a new InteropData instance using the specified properties.

#### Parameters

##### properties?

[`IInteropData`](../interfaces/IInteropData.md)

Properties to set

#### Returns

[`InteropData`](InteropData.md)

InteropData instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:9609](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9609)

Decodes an InteropData message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InteropData`](InteropData.md)

InteropData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:9618](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9618)

Decodes an InteropData message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InteropData`](InteropData.md)

InteropData

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9591](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9591)

Encodes the specified InteropData message. Does not implicitly [verify](InteropData.md#verify) messages.

#### Parameters

##### message

[`IInteropData`](../interfaces/IInteropData.md)

InteropData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:9599](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9599)

Encodes the specified InteropData message, length delimited. Does not implicitly [verify](InteropData.md#verify) messages.

#### Parameters

##### message

[`IInteropData`](../interfaces/IInteropData.md)

InteropData message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:9632](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9632)

Creates an InteropData message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InteropData`](InteropData.md)

InteropData

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9653](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9653)

Gets the default type url for InteropData

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

Defined in: [WAProto/index.d.ts:9640](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9640)

Creates a plain object from an InteropData message. Also converts values to other types if specified.

#### Parameters

##### message

[`InteropData`](InteropData.md)

InteropData

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:9625](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L9625)

Verifies an InteropData message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
