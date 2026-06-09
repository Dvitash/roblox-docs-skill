# HttpService

**Superclass:** [Instance](Instance.md)

The `HttpService` class is a class for sending HTTP requests and providing methods for interacting with web services, such as analytics, data storage, and remote server configuration.

## Tags
- NotCreatable
- Service

## Properties
### `HttpService.HttpEnabled`
- **Type:** `boolean`
- **Summary:** Indicates whether HTTP requests can be sent to external websites.

## Methods
### `HttpService:CreateWebStreamClient(streamClientType: WebStreamClientType, requestOptions: Dictionary) -> [WebStreamClient](WebStreamClient.md)`
- **Summary:** Creates a client that opens a persistent connection to stream data.

### `HttpService:GenerateGUID(wrapInCurlyBraces: boolean) -> string`
- **Summary:** Generates a UUID/GUID random string, optionally with curly braces.

### `HttpService:GetAsync(url: Variant, nocache: boolean, headers: Variant) -> string`
- **Tags:** Yields
- **Summary:** Sends an HTTP `GET` request.

### `HttpService:GetSecret(key: string) -> Secret`
- **Summary:** Returns a `Datatype.Secret` from the secrets store.

### `HttpService:JSONDecode(input: string) -> Variant`
- **Tags:** CustomLuaState
- **Summary:** Decodes a JSON string into a Luau table.

### `HttpService:JSONEncode(input: Variant) -> string`
- **Tags:** CustomLuaState
- **Summary:** Generate a JSON string from a Luau table.

### `HttpService:PostAsync(url: Variant, data: string, content_type: HttpContentType, compress: boolean, headers: Variant) -> string`
- **Tags:** Yields
- **Summary:** Sends an HTTP `POST` request.

### `HttpService:RequestAsync(requestOptions: Dictionary) -> Dictionary`
- **Tags:** Yields
- **Summary:** Sends an HTTP request using any HTTP method given a dictionary of information.

### `HttpService:UrlEncode(input: string) -> string`
- **Summary:** Replaces URL-unsafe characters with '%' and two hexadecimal characters.
