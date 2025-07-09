# Class: InteractiveMessage

Defined in: [WAProto/index.d.ts:24979](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L24979)

Represents an InteractiveMessage.

## Implements

- [`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

## Constructors

### new InteractiveMessage()

> **new InteractiveMessage**(`properties`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:24985](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L24985)

Constructs a new InteractiveMessage.

#### Parameters

##### properties?

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

Properties to set

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

## Properties

### body?

> `optional` **body**: `null` \| [`IBody`](../namespaces/InteractiveMessage/interfaces/IBody.md)

Defined in: [WAProto/index.d.ts:24991](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L24991)

InteractiveMessage body.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`body`](../interfaces/IInteractiveMessage.md#body)

***

### carouselMessage?

> `optional` **carouselMessage**: `null` \| [`ICarouselMessage`](../namespaces/InteractiveMessage/interfaces/ICarouselMessage.md)

Defined in: [WAProto/index.d.ts:25012](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25012)

InteractiveMessage carouselMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`carouselMessage`](../interfaces/IInteractiveMessage.md#carouselmessage)

***

### collectionMessage?

> `optional` **collectionMessage**: `null` \| [`ICollectionMessage`](../namespaces/InteractiveMessage/interfaces/ICollectionMessage.md)

Defined in: [WAProto/index.d.ts:25006](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25006)

InteractiveMessage collectionMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`collectionMessage`](../interfaces/IInteractiveMessage.md#collectionmessage)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:24997](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L24997)

InteractiveMessage contextInfo.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`contextInfo`](../interfaces/IInteractiveMessage.md#contextinfo)

***

### footer?

> `optional` **footer**: `null` \| [`IFooter`](../namespaces/InteractiveMessage/interfaces/IFooter.md)

Defined in: [WAProto/index.d.ts:24994](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L24994)

InteractiveMessage footer.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`footer`](../interfaces/IInteractiveMessage.md#footer)

***

### header?

> `optional` **header**: `null` \| [`IHeader`](../namespaces/InteractiveMessage/interfaces/IHeader.md)

Defined in: [WAProto/index.d.ts:24988](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L24988)

InteractiveMessage header.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`header`](../interfaces/IInteractiveMessage.md#header)

***

### interactiveMessage?

> `optional` **interactiveMessage**: `"nativeFlowMessage"` \| `"shopStorefrontMessage"` \| `"collectionMessage"` \| `"carouselMessage"`

Defined in: [WAProto/index.d.ts:25015](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25015)

InteractiveMessage interactiveMessage.

***

### nativeFlowMessage?

> `optional` **nativeFlowMessage**: `null` \| [`INativeFlowMessage`](../namespaces/InteractiveMessage/interfaces/INativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:25009](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25009)

InteractiveMessage nativeFlowMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`nativeFlowMessage`](../interfaces/IInteractiveMessage.md#nativeflowmessage)

***

### shopStorefrontMessage?

> `optional` **shopStorefrontMessage**: `null` \| [`IShopMessage`](../namespaces/InteractiveMessage/interfaces/IShopMessage.md)

Defined in: [WAProto/index.d.ts:25003](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25003)

InteractiveMessage shopStorefrontMessage.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`shopStorefrontMessage`](../interfaces/IInteractiveMessage.md#shopstorefrontmessage)

***

### urlTrackingMap?

> `optional` **urlTrackingMap**: `null` \| [`IUrlTrackingMap`](../../../interfaces/IUrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:25000](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25000)

InteractiveMessage urlTrackingMap.

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`urlTrackingMap`](../interfaces/IInteractiveMessage.md#urltrackingmap)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25085](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25085)

Converts this InteractiveMessage to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:25022](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25022)

Creates a new InteractiveMessage instance using the specified properties.

#### Parameters

##### properties?

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

Properties to set

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:25048](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25048)

Decodes an InteractiveMessage message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:25057](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25057)

Decodes an InteractiveMessage message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25030](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25030)

Encodes the specified InteractiveMessage message. Does not implicitly [verify](InteractiveMessage.md#verify) messages.

#### Parameters

##### message

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

InteractiveMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:25038](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25038)

Encodes the specified InteractiveMessage message, length delimited. Does not implicitly [verify](InteractiveMessage.md#verify) messages.

#### Parameters

##### message

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

InteractiveMessage message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:25071](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25071)

Creates an InteractiveMessage message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:25092](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25092)

Gets the default type url for InteractiveMessage

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

Defined in: [WAProto/index.d.ts:25079](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25079)

Creates a plain object from an InteractiveMessage message. Also converts values to other types if specified.

#### Parameters

##### message

[`InteractiveMessage`](InteractiveMessage.md)

InteractiveMessage

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:25064](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/WAProto/index.d.ts#L25064)

Verifies an InteractiveMessage message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
