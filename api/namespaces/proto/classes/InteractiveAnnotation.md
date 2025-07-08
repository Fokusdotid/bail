# Class: InteractiveAnnotation

Defined in: [WAProto/index.d.ts:16662](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16662)

Represents an InteractiveAnnotation.

## Implements

- [`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

## Constructors

### new InteractiveAnnotation()

> **new InteractiveAnnotation**(`properties`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:16668](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16668)

Constructs a new InteractiveAnnotation.

#### Parameters

##### properties?

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

Properties to set

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

## Properties

### action?

> `optional` **action**: `"location"` \| `"newsletter"` \| `"embeddedAction"` \| `"tapAction"`

Defined in: [WAProto/index.d.ts:16695](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16695)

InteractiveAnnotation action.

***

### embeddedAction?

> `optional` **embeddedAction**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:16689](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16689)

InteractiveAnnotation embeddedAction.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`embeddedAction`](../interfaces/IInteractiveAnnotation.md#embeddedaction)

***

### embeddedContent?

> `optional` **embeddedContent**: `null` \| [`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

Defined in: [WAProto/index.d.ts:16677](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16677)

InteractiveAnnotation embeddedContent.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`embeddedContent`](../interfaces/IInteractiveAnnotation.md#embeddedcontent)

***

### location?

> `optional` **location**: `null` \| [`ILocation`](../interfaces/ILocation.md)

Defined in: [WAProto/index.d.ts:16683](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16683)

InteractiveAnnotation location.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`location`](../interfaces/IInteractiveAnnotation.md#location)

***

### newsletter?

> `optional` **newsletter**: `null` \| [`IForwardedNewsletterMessageInfo`](../namespaces/ContextInfo/interfaces/IForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:16686](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16686)

InteractiveAnnotation newsletter.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`newsletter`](../interfaces/IInteractiveAnnotation.md#newsletter)

***

### polygonVertices

> **polygonVertices**: [`IPoint`](../interfaces/IPoint.md)[]

Defined in: [WAProto/index.d.ts:16671](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16671)

InteractiveAnnotation polygonVertices.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`polygonVertices`](../interfaces/IInteractiveAnnotation.md#polygonvertices)

***

### shouldSkipConfirmation?

> `optional` **shouldSkipConfirmation**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:16674](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16674)

InteractiveAnnotation shouldSkipConfirmation.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`shouldSkipConfirmation`](../interfaces/IInteractiveAnnotation.md#shouldskipconfirmation)

***

### statusLinkType?

> `optional` **statusLinkType**: `null` \| [`StatusLinkType`](../namespaces/InteractiveAnnotation/enumerations/StatusLinkType.md)

Defined in: [WAProto/index.d.ts:16680](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16680)

InteractiveAnnotation statusLinkType.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`statusLinkType`](../interfaces/IInteractiveAnnotation.md#statuslinktype)

***

### tapAction?

> `optional` **tapAction**: `null` \| [`ITapLinkAction`](../interfaces/ITapLinkAction.md)

Defined in: [WAProto/index.d.ts:16692](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16692)

InteractiveAnnotation tapAction.

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`tapAction`](../interfaces/IInteractiveAnnotation.md#tapaction)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16765](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16765)

Converts this InteractiveAnnotation to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:16702](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16702)

Creates a new InteractiveAnnotation instance using the specified properties.

#### Parameters

##### properties?

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

Properties to set

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:16728](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16728)

Decodes an InteractiveAnnotation message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:16737](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16737)

Decodes an InteractiveAnnotation message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16710](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16710)

Encodes the specified InteractiveAnnotation message. Does not implicitly [verify](InteractiveAnnotation.md#verify) messages.

#### Parameters

##### message

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

InteractiveAnnotation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16718](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16718)

Encodes the specified InteractiveAnnotation message, length delimited. Does not implicitly [verify](InteractiveAnnotation.md#verify) messages.

#### Parameters

##### message

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

InteractiveAnnotation message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:16751](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16751)

Creates an InteractiveAnnotation message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:16772](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16772)

Gets the default type url for InteractiveAnnotation

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

Defined in: [WAProto/index.d.ts:16759](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16759)

Creates a plain object from an InteractiveAnnotation message. Also converts values to other types if specified.

#### Parameters

##### message

[`InteractiveAnnotation`](InteractiveAnnotation.md)

InteractiveAnnotation

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16744](https://github.com/Fokusdotid/bail/blob/99acc683da8779d62a0509bb4108fdb35cb2b061/WAProto/index.d.ts#L16744)

Verifies an InteractiveAnnotation message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
