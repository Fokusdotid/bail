# Class: PaymentInfo

Defined in: [WAProto/index.d.ts:38630](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38630)

Represents a PaymentInfo.

## Implements

- [`IPaymentInfo`](../interfaces/IPaymentInfo.md)

## Constructors

### new PaymentInfo()

> **new PaymentInfo**(`properties`?): [`PaymentInfo`](PaymentInfo.md)

Defined in: [WAProto/index.d.ts:38636](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38636)

Constructs a new PaymentInfo.

#### Parameters

##### properties?

[`IPaymentInfo`](../interfaces/IPaymentInfo.md)

Properties to set

#### Returns

[`PaymentInfo`](PaymentInfo.md)

## Properties

### amount1000?

> `optional` **amount1000**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:38642](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38642)

PaymentInfo amount1000.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`amount1000`](../interfaces/IPaymentInfo.md#amount1000)

***

### currency?

> `optional` **currency**: `null` \| `string`

Defined in: [WAProto/index.d.ts:38663](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38663)

PaymentInfo currency.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`currency`](../interfaces/IPaymentInfo.md#currency)

***

### currencyDeprecated?

> `optional` **currencyDeprecated**: `null` \| [`Currency`](../namespaces/PaymentInfo/enumerations/Currency.md)

Defined in: [WAProto/index.d.ts:38639](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38639)

PaymentInfo currencyDeprecated.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`currencyDeprecated`](../interfaces/IPaymentInfo.md#currencydeprecated)

***

### exchangeAmount?

> `optional` **exchangeAmount**: `null` \| [`IMoney`](../interfaces/IMoney.md)

Defined in: [WAProto/index.d.ts:38675](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38675)

PaymentInfo exchangeAmount.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`exchangeAmount`](../interfaces/IPaymentInfo.md#exchangeamount)

***

### expiryTimestamp?

> `optional` **expiryTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:38657](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38657)

PaymentInfo expiryTimestamp.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`expiryTimestamp`](../interfaces/IPaymentInfo.md#expirytimestamp)

***

### futureproofed?

> `optional` **futureproofed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:38660](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38660)

PaymentInfo futureproofed.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`futureproofed`](../interfaces/IPaymentInfo.md#futureproofed)

***

### primaryAmount?

> `optional` **primaryAmount**: `null` \| [`IMoney`](../interfaces/IMoney.md)

Defined in: [WAProto/index.d.ts:38672](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38672)

PaymentInfo primaryAmount.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`primaryAmount`](../interfaces/IPaymentInfo.md#primaryamount)

***

### receiverJid?

> `optional` **receiverJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:38645](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38645)

PaymentInfo receiverJid.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`receiverJid`](../interfaces/IPaymentInfo.md#receiverjid)

***

### requestMessageKey?

> `optional` **requestMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:38654](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38654)

PaymentInfo requestMessageKey.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`requestMessageKey`](../interfaces/IPaymentInfo.md#requestmessagekey)

***

### status?

> `optional` **status**: `null` \| [`Status`](../namespaces/PaymentInfo/enumerations/Status.md)

Defined in: [WAProto/index.d.ts:38648](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38648)

PaymentInfo status.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`status`](../interfaces/IPaymentInfo.md#status)

***

### transactionTimestamp?

> `optional` **transactionTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:38651](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38651)

PaymentInfo transactionTimestamp.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`transactionTimestamp`](../interfaces/IPaymentInfo.md#transactiontimestamp)

***

### txnStatus?

> `optional` **txnStatus**: `null` \| [`TxnStatus`](../namespaces/PaymentInfo/enumerations/TxnStatus.md)

Defined in: [WAProto/index.d.ts:38666](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38666)

PaymentInfo txnStatus.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`txnStatus`](../interfaces/IPaymentInfo.md#txnstatus)

***

### useNoviFiatFormat?

> `optional` **useNoviFiatFormat**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:38669](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38669)

PaymentInfo useNoviFiatFormat.

#### Implementation of

[`IPaymentInfo`](../interfaces/IPaymentInfo.md).[`useNoviFiatFormat`](../interfaces/IPaymentInfo.md#usenovifiatformat)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:38745](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38745)

Converts this PaymentInfo to JSON.

#### Returns

`object`

JSON object

***

### create()

> `static` **create**(`properties`?): [`PaymentInfo`](PaymentInfo.md)

Defined in: [WAProto/index.d.ts:38682](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38682)

Creates a new PaymentInfo instance using the specified properties.

#### Parameters

##### properties?

[`IPaymentInfo`](../interfaces/IPaymentInfo.md)

Properties to set

#### Returns

[`PaymentInfo`](PaymentInfo.md)

PaymentInfo instance

***

### decode()

> `static` **decode**(`reader`, `length`?): [`PaymentInfo`](PaymentInfo.md)

Defined in: [WAProto/index.d.ts:38708](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38708)

Decodes a PaymentInfo message from the specified reader or buffer.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### length?

`number`

Message length if known beforehand

#### Returns

[`PaymentInfo`](PaymentInfo.md)

PaymentInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### decodeDelimited()

> `static` **decodeDelimited**(`reader`): [`PaymentInfo`](PaymentInfo.md)

Defined in: [WAProto/index.d.ts:38717](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38717)

Decodes a PaymentInfo message from the specified reader or buffer, length delimited.

#### Parameters

##### reader

Reader or buffer to decode from

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

#### Returns

[`PaymentInfo`](PaymentInfo.md)

PaymentInfo

#### Throws

If the payload is not a reader or valid buffer

#### Throws

If required fields are missing

***

### encode()

> `static` **encode**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38690](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38690)

Encodes the specified PaymentInfo message. Does not implicitly [verify](PaymentInfo.md#verify) messages.

#### Parameters

##### message

[`IPaymentInfo`](../interfaces/IPaymentInfo.md)

PaymentInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### encodeDelimited()

> `static` **encodeDelimited**(`message`, `writer`?): `Writer`

Defined in: [WAProto/index.d.ts:38698](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38698)

Encodes the specified PaymentInfo message, length delimited. Does not implicitly [verify](PaymentInfo.md#verify) messages.

#### Parameters

##### message

[`IPaymentInfo`](../interfaces/IPaymentInfo.md)

PaymentInfo message or plain object to encode

##### writer?

`Writer`

Writer to encode to

#### Returns

`Writer`

Writer

***

### fromObject()

> `static` **fromObject**(`object`): [`PaymentInfo`](PaymentInfo.md)

Defined in: [WAProto/index.d.ts:38731](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38731)

Creates a PaymentInfo message from a plain object. Also converts values to their respective internal types.

#### Parameters

##### object

Plain object

#### Returns

[`PaymentInfo`](PaymentInfo.md)

PaymentInfo

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:38752](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38752)

Gets the default type url for PaymentInfo

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

Defined in: [WAProto/index.d.ts:38739](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38739)

Creates a plain object from a PaymentInfo message. Also converts values to other types if specified.

#### Parameters

##### message

[`PaymentInfo`](PaymentInfo.md)

PaymentInfo

##### options?

`IConversionOptions`

Conversion options

#### Returns

`object`

Plain object

***

### verify()

> `static` **verify**(`message`): `null` \| `string`

Defined in: [WAProto/index.d.ts:38724](https://github.com/Fokusdotid/bail/blob/3856b89f13bbe82f2e10396a28cd4ef2089de845/WAProto/index.d.ts#L38724)

Verifies a PaymentInfo message.

#### Parameters

##### message

Plain object to verify

#### Returns

`null` \| `string`

`null` if valid, otherwise the reason why it is not
