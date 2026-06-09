# ServiceProvider

**Superclass:** [Instance](Instance.md)

A ServiceProvider class is an abstract class that provides a singleton instance for specific classes based on inherited types.

## Tags
- NotCreatable
- NotBrowsable

## Methods
### `ServiceProvider:FindService(className: string) -> [Instance](Instance.md)`
- **Summary:** Returns the service specified by the given className if it's already created, errors for an invalid name.

### `ServiceProvider:GetService(className: string) -> [Instance](Instance.md)`
- **Summary:** Returns the service with the requested class name, creating it if it does not exist.

### `ServiceProvider:getService(className: string) -> [Instance](Instance.md)`
- **Tags:** Deprecated

### `ServiceProvider:service(className: string) -> [Instance](Instance.md)`
- **Tags:** Deprecated

## Events
### `ServiceProvider.Close()`
- **Summary:** Fires when the current place is exited.

### `ServiceProvider.ServiceAdded(service: [Instance](Instance.md))`
- **Summary:** Fired when a service is created.

### `ServiceProvider.ServiceRemoving(service: [Instance](Instance.md))`
- **Summary:** Fired when a service is about to be removed.
