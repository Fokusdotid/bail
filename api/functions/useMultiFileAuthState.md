# Function: useMultiFileAuthState()

> **useMultiFileAuthState**(`folder`): `Promise`\<\{ `saveCreds`: () => `Promise`\<`void`\>; `state`: [`AuthenticationState`](../type-aliases/AuthenticationState.md); \}\>

Defined in: [src/Utils/use-multi-file-auth-state.ts:33](https://github.com/Fokusdotid/bail/blob/a1b2bb6d3d63874a4f497e70ebd6347b2869da8e/src/Utils/use-multi-file-auth-state.ts#L33)

stores the full authentication state in a single folder.
Far more efficient than singlefileauthstate

Again, I wouldn't endorse this for any production level use other than perhaps a bot.
Would recommend writing an auth state for use with a proper SQL or No-SQL DB

## Parameters

### folder

`string`

## Returns

`Promise`\<\{ `saveCreds`: () => `Promise`\<`void`\>; `state`: [`AuthenticationState`](../type-aliases/AuthenticationState.md); \}\>
