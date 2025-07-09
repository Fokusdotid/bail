# Class: LIDMigrationMappingSyncMessage

Defined in: [WAProto/index.d.ts:17254](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17254)

Represents a LIDMigrationMappingSyncMessage.

## Implements

- [`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

## Constructors

### new LIDMigrationMappingSyncMessage()

> **new LIDMigrationMappingSyncMessage**(`properties`?): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:17260](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17260)

Constructs a new LIDMigrationMappingSyncMessage.

#### Parameters

##### properties?

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

Properties to set

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

## Properties

### encodedMappingPayload?

> `optional` **encodedMappingPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:17263](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17263)

LIDMigrationMappingSyncMessage encodedMappingPayload.

#### Implementation of

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md).[`encodedMappingPayload`](../interfaces/ILIDMigrationMappingSyncMessage.md#encodedmappingpayload)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17333](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17333)

Converts this LIDMigrationMappingSyncMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:17270](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17270)

Creates a new LIDMigrationMappingSyncMessage instance using the specified properties.

#### Parameters

##### properties?

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

Properties to set

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

LIDMigrationMappingSyncMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:17296](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17296)

Decodes a LIDMigrationMappingSyncMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

LIDMigrationMappingSyncMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:17305](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17305)

Decodes a LIDMigrationMappingSyncMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

LIDMigrationMappingSyncMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17278](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17278)

Encodes the specified LIDMigrationMappingSyncMessage message. Does not implicitly [verify](LIDMigrationMappingSyncMessage.md#verify) messages.

#### Parameters

##### message

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

LIDMigrationMappingSyncMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17286](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17286)

Encodes the specified LIDMigrationMappingSyncMessage message, length delimited. Does not implicitly [verify](LIDMigrationMappingSyncMessage.md#verify) messages.

#### Parameters

##### message

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

LIDMigrationMappingSyncMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:17319](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17319)

Creates a LIDMigrationMappingSyncMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

LIDMigrationMappingSyncMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:17340](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17340)

Gets the default type url for LIDMigrationMappingSyncMessage

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

Defined in: [WAProto/index.d.ts:17327](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17327)

Creates a plain object from a LIDMigrationMappingSyncMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

LIDMigrationMappingSyncMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17312](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L17312)

Verifies a LIDMigrationMappingSyncMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
