# Type Alias: EventInputType

> **EventInputType**: `{ [key in Event["name"]]: { globals: (x: string) => Value; props: { [k in keyof EventByName<key>["props"]]: Value } } }` & `object`

Defined in: [src/WAM/constants.ts:15267](https://github.com/Fokusdotid/bail/blob/3bcafd64e13ba51a595ace0ee7bd2c9c52ab1814/src/WAM/constants.ts#L15267)
