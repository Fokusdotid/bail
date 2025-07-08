# Function: debouncedTimeout()

> **debouncedTimeout**(`intervalMs`, `task`?): `object`

Defined in: [src/Utils/generics.ts:115](https://github.com/Fokusdotid/bail/blob/0fe6346a5ff68a74eb71890335c982b44e2da604/src/Utils/generics.ts#L115)

## Parameters

### intervalMs

`number` = `1000`

### task?

() => `void`

## Returns

`object`

### cancel()

> **cancel**: () => `void`

#### Returns

`void`

### setInterval()

> **setInterval**: (`newInterval`) => `number`

#### Parameters

##### newInterval

`number`

#### Returns

`number`

### setTask()

> **setTask**: (`newTask`) => () => `void`

#### Parameters

##### newTask

() => `void`

#### Returns

`Function`

##### Returns

`void`

### start()

> **start**: (`newIntervalMs`?, `newTask`?) => `void`

#### Parameters

##### newIntervalMs?

`number`

##### newTask?

() => `void`

#### Returns

`void`
