# bevy_gearbox_macros

Procedural macros for the `bevy_gearbox` crate. This crate provides the `state_machine!` macro that generates state machine infrastructure for Bevy entities.

## Version Compatibility

| bevy_gearbox_macros | bevy_gearbox | bevy |
|---------------------|--------------|------|
| 0.2.0               | 0.2.0        | 0.16 |
| 0.1.0               | 0.1.2        | 0.16 |

## Usage

This crate is automatically included when you use `bevy_gearbox`. You don't need to add it as a direct dependency unless you're doing advanced macro work.

```rust
use bevy_gearbox::prelude::*;

// This macro is provided by bevy_gearbox_macros
state_machine!(Player;
    IdleState,
    RunningState,
    JumpingState
);
```

For full documentation and examples, see the main [`bevy_gearbox`](https://crates.io/crates/bevy_gearbox) crate.

