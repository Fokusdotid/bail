# Interface: NewsletterCreateResponse

Defined in: [src/Types/Newsletter.ts:34](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/src/Types/Newsletter.ts#L34)

## Properties

### id

> **id**: `string`

Defined in: [src/Types/Newsletter.ts:35](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/src/Types/Newsletter.ts#L35)

***

### state

> **state**: `object`

Defined in: [src/Types/Newsletter.ts:36](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/src/Types/Newsletter.ts#L36)

#### type

> **type**: `string`

***

### thread\_metadata

> **thread\_metadata**: `object`

Defined in: [src/Types/Newsletter.ts:37](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/src/Types/Newsletter.ts#L37)

#### creation\_time

> **creation\_time**: `string`

#### description

> **description**: `object`

##### description.id

> **id**: `string`

##### description.text

> **text**: `string`

##### description.update\_time

> **update\_time**: `string`

#### handle

> **handle**: `null` \| `string`

#### invite

> **invite**: `string`

#### name

> **name**: `object`

##### name.id

> **id**: `string`

##### name.text

> **text**: `string`

##### name.update\_time

> **update\_time**: `string`

#### picture

> **picture**: `object`

##### picture.direct\_path

> **direct\_path**: `string`

##### picture.id

> **id**: `string`

##### picture.type

> **type**: `string`

#### preview

> **preview**: `object`

##### preview.direct\_path

> **direct\_path**: `string`

##### preview.id

> **id**: `string`

##### preview.type

> **type**: `string`

#### subscribers\_count

> **subscribers\_count**: `string`

#### verification

> **verification**: `"VERIFIED"` \| `"UNVERIFIED"`

***

### viewer\_metadata

> **viewer\_metadata**: `object`

Defined in: [src/Types/Newsletter.ts:48](https://github.com/Fokusdotid/bail/blob/82f46c566476ac566bfd781dede14412fcdfb787/src/Types/Newsletter.ts#L48)

#### mute

> **mute**: `"ON"` \| `"OFF"`

#### role

> **role**: [`NewsletterViewRole`](../type-aliases/NewsletterViewRole.md)
