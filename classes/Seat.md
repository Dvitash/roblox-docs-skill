# Seat

**Superclass:** [Part](Part.md)

Seats are a type of `Class.BasePart` that allows characters to 'sit' in moving objects, and they can be used for creating chairs or interfaces.

## Properties
### `Seat.Disabled`
- **Type:** `boolean`
- **Summary:** Whether or not the seat is usable. If set to true, the seat will act as a normal part.

### `Seat.Occupant`
- **Type:** `[Humanoid](Humanoid.md)`
- **Tags:** ReadOnly, NotReplicated
- **Summary:** The humanoid that is sitting in the seat.

## Methods
### `Seat:Sit(humanoid: [Instance](Instance.md)) -> ()`
- **Summary:** Forces the character with the specified `Class.Humanoid` to sit in the Seat.
