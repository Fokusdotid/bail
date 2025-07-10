# Interface: Contact

Defined in: [src/Types/Contact.ts:1](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L1)

## Properties

### id

> **id**: `string`

Defined in: [src/Types/Contact.ts:3](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L3)

ID either in lid or jid format *

***

### imgUrl?

> `optional` **imgUrl**: `null` \| `string`

Defined in: [src/Types/Contact.ts:22](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L22)

Url of the profile picture of the contact

'changed' => if the profile picture has changed
null => if the profile picture has not been set (default profile picture)
any other string => url of the profile picture

***

### jid?

> `optional` **jid**: `string`

Defined in: [src/Types/Contact.ts:7](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L7)

ID in Phone Number format (@s.whatsapp.net)  *

***

### lid?

> `optional` **lid**: `string`

Defined in: [src/Types/Contact.ts:5](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L5)

ID in Lid (anonymous) format (@lid) *

***

### name?

> `optional` **name**: `string`

Defined in: [src/Types/Contact.ts:9](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L9)

name of the contact, you have saved on your WA

***

### notify?

> `optional` **notify**: `string`

Defined in: [src/Types/Contact.ts:11](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L11)

name of the contact, the contact has set on their own on WA

***

### status?

> `optional` **status**: `string`

Defined in: [src/Types/Contact.ts:23](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L23)

***

### verifiedName?

> `optional` **verifiedName**: `string`

Defined in: [src/Types/Contact.ts:13](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/Types/Contact.ts#L13)

I have no idea
