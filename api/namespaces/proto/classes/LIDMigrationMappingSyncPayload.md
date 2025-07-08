# Class: LIDMigrationMappingSyncPayload

Defined in: [WAProto/index.d.ts:17354](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17354)

Represents a LIDMigrationMappingSyncPayload.

## Implements

- [`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

## Constructors

### new LIDMigrationMappingSyncPayload()

> **new LIDMigrationMappingSyncPayload**(`properties`?): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:17360](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17360)

Constructs a new LIDMigrationMappingSyncPayload.

#### Parameters

##### properties?

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

Properties to set

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

## Properties

### chatDbMigrationTimestamp?

> `optional` **chatDbMigrationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:17366](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17366)

LIDMigrationMappingSyncPayload chatDbMigrationTimestamp.

#### Implementation of

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md).[`chatDbMigrationTimestamp`](../interfaces/ILIDMigrationMappingSyncPayload.md#chatdbmigrationtimestamp)

***

### pnToLidMappings

> **pnToLidMappings**: [`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)[]

Defined in: [WAProto/index.d.ts:17363](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17363)

LIDMigrationMappingSyncPayload pnToLidMappings.

#### Implementation of

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md).[`pnToLidMappings`](../interfaces/ILIDMigrationMappingSyncPayload.md#pntolidmappings)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:17436](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17436)

Converts this LIDMigrationMappingSyncPayload to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:17373](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17373)

Creates a new LIDMigrationMappingSyncPayload instance using the specified properties.

#### Parameters

##### properties?

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

Properties to set

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

LIDMigrationMappingSyncPayload instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:17399](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17399)

Decodes a LIDMigrationMappingSyncPayload message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

LIDMigrationMappingSyncPayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:17408](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17408)

Decodes a LIDMigrationMappingSyncPayload message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

LIDMigrationMappingSyncPayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17381](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17381)

Encodes the specified LIDMigrationMappingSyncPayload message. Does not implicitly [verify](LIDMigrationMappingSyncPayload.md#verify) messages.

#### Parameters

##### message

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

LIDMigrationMappingSyncPayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:17389](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17389)

Encodes the specified LIDMigrationMappingSyncPayload message, length delimited. Does not implicitly [verify](LIDMigrationMappingSyncPayload.md#verify) messages.

#### Parameters

##### message

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

LIDMigrationMappingSyncPayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:17422](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17422)

Creates a LIDMigrationMappingSyncPayload message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

LIDMigrationMappingSyncPayload

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:17443](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17443)

Gets the default type url for LIDMigrationMappingSyncPayload

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

Defined in: [WAProto/index.d.ts:17430](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17430)

Creates a plain object from a LIDMigrationMappingSyncPayload message. Also converts values to other types if specified.

#### Parameters

##### message

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

LIDMigrationMappingSyncPayload

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:17415](https://github.com/Fokusdotid/bail/blob/8a30cf93a8ac726f06d1ad6578695812a8253e53/WAProto/index.d.ts#L17415)

Verifies a LIDMigrationMappingSyncPayload message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
