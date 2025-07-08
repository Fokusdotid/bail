# Class: ProloguePayload

Defined in: [WAProto/index.d.ts:40199](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40199)

Represents a ProloguePayload.

## Implements

- [`IProloguePayload`](../interfaces/IProloguePayload.md)

## Constructors

### new ProloguePayload()

> **new ProloguePayload**(`properties`?): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:40205](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40205)

Constructs a new ProloguePayload.

#### Parameters

##### properties?

[`IProloguePayload`](../interfaces/IProloguePayload.md)

Properties to set

#### Returns

[`ProloguePayload`](ProloguePayload.md)

## Properties

### commitment?

> `optional` **commitment**: `null` \| [`ICompanionCommitment`](../interfaces/ICompanionCommitment.md)

Defined in: [WAProto/index.d.ts:40211](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40211)

ProloguePayload commitment.

#### Implementation of

[`IProloguePayload`](../interfaces/IProloguePayload.md).[`commitment`](../interfaces/IProloguePayload.md#commitment)

***

### companionEphemeralIdentity?

> `optional` **companionEphemeralIdentity**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:40208](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40208)

ProloguePayload companionEphemeralIdentity.

#### Implementation of

[`IProloguePayload`](../interfaces/IProloguePayload.md).[`companionEphemeralIdentity`](../interfaces/IProloguePayload.md#companionephemeralidentity)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:40281](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40281)

Converts this ProloguePayload to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:40218](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40218)

Creates a new ProloguePayload instance using the specified properties.

#### Parameters

##### properties?

[`IProloguePayload`](../interfaces/IProloguePayload.md)

Properties to set

#### Returns

[`ProloguePayload`](ProloguePayload.md)

ProloguePayload instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:40244](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40244)

Decodes a ProloguePayload message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`ProloguePayload`](ProloguePayload.md)

ProloguePayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:40253](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40253)

Decodes a ProloguePayload message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`ProloguePayload`](ProloguePayload.md)

ProloguePayload

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40226](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40226)

Encodes the specified ProloguePayload message. Does not implicitly [verify](ProloguePayload.md#verify) messages.

#### Parameters

##### message

[`IProloguePayload`](../interfaces/IProloguePayload.md)

ProloguePayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:40234](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40234)

Encodes the specified ProloguePayload message, length delimited. Does not implicitly [verify](ProloguePayload.md#verify) messages.

#### Parameters

##### message

[`IProloguePayload`](../interfaces/IProloguePayload.md)

ProloguePayload message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:40267](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40267)

Creates a ProloguePayload message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`ProloguePayload`](ProloguePayload.md)

ProloguePayload

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:40288](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40288)

Gets the default type url for ProloguePayload

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

Defined in: [WAProto/index.d.ts:40275](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40275)

Creates a plain object from a ProloguePayload message. Also converts values to other types if specified.

#### Parameters

##### message

[`ProloguePayload`](ProloguePayload.md)

ProloguePayload

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:40260](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L40260)

Verifies a ProloguePayload message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
