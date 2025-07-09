# Class: HydratedURLButton

Defined in: [WAProto/index.d.ts:16421](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16421)

Represents a HydratedURLButton.

## Implements

- [`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

## Constructors

### new HydratedURLButton()

> **new HydratedURLButton**(`properties`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:16427](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16427)

Constructs a new HydratedURLButton.

#### Parameters

##### properties?

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

Properties to set

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

## Properties

### consentedUsersUrl?

> `optional` **consentedUsersUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16436](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16436)

HydratedURLButton consentedUsersUrl.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`consentedUsersUrl`](../interfaces/IHydratedURLButton.md#consentedusersurl)

***

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16430](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16430)

HydratedURLButton displayText.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`displayText`](../interfaces/IHydratedURLButton.md#displaytext)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:16433](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16433)

HydratedURLButton url.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`url`](../interfaces/IHydratedURLButton.md#url)

***

### webviewPresentation?

> `optional` **webviewPresentation**: `null` \| [`WebviewPresentationType`](../namespaces/HydratedURLButton/enumerations/WebviewPresentationType.md)

Defined in: [WAProto/index.d.ts:16439](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16439)

HydratedURLButton webviewPresentation.

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`webviewPresentation`](../interfaces/IHydratedURLButton.md#webviewpresentation)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:16509](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16509)

Converts this HydratedURLButton to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:16446](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16446)

Creates a new HydratedURLButton instance using the specified properties.

#### Parameters

##### properties?

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

Properties to set

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:16472](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16472)

Decodes a HydratedURLButton message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:16481](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16481)

Decodes a HydratedURLButton message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16454](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16454)

Encodes the specified HydratedURLButton message. Does not implicitly [verify](HydratedURLButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

HydratedURLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:16462](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16462)

Encodes the specified HydratedURLButton message, length delimited. Does not implicitly [verify](HydratedURLButton.md#verify) messages.

#### Parameters

##### message

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

HydratedURLButton message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:16495](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16495)

Creates a HydratedURLButton message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:16516](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16516)

Gets the default type url for HydratedURLButton

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

Defined in: [WAProto/index.d.ts:16503](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16503)

Creates a plain object from a HydratedURLButton message. Also converts values to other types if specified.

#### Parameters

##### message

[`HydratedURLButton`](HydratedURLButton.md)

HydratedURLButton

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:16488](https://github.com/Fokusdotid/bail/blob/cf6cc85134e12081bc635cea02cc0eee74033a81/WAProto/index.d.ts#L16488)

Verifies a HydratedURLButton message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
