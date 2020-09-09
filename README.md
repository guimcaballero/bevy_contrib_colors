# Bevy color library

Color library for the [Bevy](https://github.com/bevyengine/bevy) game engine.

It currently contains the [Tailwind color palette](https://tailwindcss.com/docs/customizing-colors#default-color-palette), but feel free to open a PR to add more!

## How to use

Add the project as a dependency in `Cargo.toml`:

```
bevy_contrib_colors = "0.1.0"
```

Just import `bevy_contrib_colors::Tailwind` and use like so:

```rust
    use bevy::render::color::Color;
    use bevy_contrib_colors::Tailwind;

    let red: Color = Tailwind::RED400; // #FC8181
    let blue: Color = Tailwind::BLUE600; // #3182CE
```
