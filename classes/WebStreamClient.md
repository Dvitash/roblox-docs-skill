# WebStreamClient

**Superclass:** [Object](Object.md)

WebStreamClient is a class used to manage a streaming connection, allowing for processing stream events and handling errors.

## Tags
- NotCreatable
- NotReplicated

## Properties
### `WebStreamClient.ConnectionState`
- **Type:** `WebStreamClientState`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The current `Enum.WebStreamClientState` of the client.

## Methods
### `WebStreamClient:Close() -> ()`
- **Summary:** Closes the client, aborting the ongoing request.

### `WebStreamClient:Send(data: string) -> ()`
- **Summary:** Enqueues data to be transmitted to the server over the streaming connection.

## Events
### `WebStreamClient.Closed()`

### `WebStreamClient.Error(responseStatusCode: int, errorMessage: string)`
- **Summary:** Fires if an error is received while establishing the connection or during the connection lifetime.

### `WebStreamClient.MessageReceived(message: string)`
- **Summary:** Fires each time a message is received from the server.

### `WebStreamClient.Opened(responseStatusCode: int, headers: string)`
- **Summary:** Fires when the a connection is successfully established between the client and server, allowing for events to begin streaming.
