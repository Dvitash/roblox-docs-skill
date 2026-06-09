# LogService

**Superclass:** [Instance](Instance.md)

The `LogService` class is a service that allows users to log structured text and read outputted text, providing basic logging capabilities for Roblox Studio.

## Tags
- NotCreatable
- Service

## Methods
### `LogService:ClearOutput() -> ()`
- **Summary:** Clears Roblox Studio's **Output** window.

### `LogService:Error(message: string, context: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Logs a message at the `Enum.MessageType.MessageError` level and throws a structured error with optional context.

### `LogService:GetLogHistory() -> Array`
- **Summary:** Returns a table of tables, each with the message string, message type, and timestamp of a message that the client displays in the **Output** window.

### `LogService:Info(message: string, context: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Logs a message at the `Enum.MessageType.MessageInfo` level with optional structured context.

### `LogService:Log(messageType: MessageType, message: string, context: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Logs a message at the specified level with optional structured context.

### `LogService:Output(message: string, context: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Logs a message at the `Enum.MessageType.MessageOutput` level with optional structured context.

### `LogService:Warn(message: string, context: Dictionary) -> ()`
- **Tags:** CustomLuaState
- **Summary:** Logs a message at the `Enum.MessageType.MessageWarning` level with optional structured context.

## Events
### `LogService.MessageOut(message: string, messageType: MessageType, context: Dictionary)`
- **Summary:** Fires when the client outputs text.
