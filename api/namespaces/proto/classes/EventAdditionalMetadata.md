# Class: EventAdditionalMetadata

Defined in: [WAProto/index.d.ts:14347](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14347)

Represents an EventAdditionalMetadata.

## Implements

- [`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

## Constructors

### new EventAdditionalMetadata()

> **new EventAdditionalMetadata**(`properties`?): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:14353](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14353)

Constructs a new EventAdditionalMetadata.

#### Parameters

##### properties?

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

Properties to set

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

## Properties

### isStale?

> `optional` **isStale**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:14356](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14356)

EventAdditionalMetadata isStale.

#### Implementation of

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md).[`isStale`](../interfaces/IEventAdditionalMetadata.md#isstale)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14426](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14426)

Converts this EventAdditionalMetadata to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:14363](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14363)

Creates a new EventAdditionalMetadata instance using the specified properties.

#### Parameters

##### properties?

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

Properties to set

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

EventAdditionalMetadata instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:14389](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14389)

Decodes an EventAdditionalMetadata message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

EventAdditionalMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:14398](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14398)

Decodes an EventAdditionalMetadata message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

EventAdditionalMetadata

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14371](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14371)

Encodes the specified EventAdditionalMetadata message. Does not implicitly [verify](EventAdditionalMetadata.md#verify) messages.

#### Parameters

##### message

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

EventAdditionalMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:14379](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14379)

Encodes the specified EventAdditionalMetadata message, length delimited. Does not implicitly [verify](EventAdditionalMetadata.md#verify) messages.

#### Parameters

##### message

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

EventAdditionalMetadata message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:14412](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14412)

Creates an EventAdditionalMetadata message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

EventAdditionalMetadata

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:14433](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14433)

Gets the default type url for EventAdditionalMetadata

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

Defined in: [WAProto/index.d.ts:14420](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14420)

Creates a plain object from an EventAdditionalMetadata message. Also converts values to other types if specified.

#### Parameters

##### message

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

EventAdditionalMetadata

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:14405](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L14405)

Verifies an EventAdditionalMetadata message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
