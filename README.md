# tuple_swizzle

[![Crates.io](https://crates.io/crates.io/tuple_swizzle)](https://crates.io/crates/tuple_swizzle)

[![Docs.rs](https://docs.rs/tuple_swizzle)](https://docs.rs/tuple_swizzle)

# Using in your project

~~~
tuple_swizzle = "1.0.1"
~~~

tuple_swizzle adds swizzle operations( such as `(1, 255, 255, 255).bgra()`, `(1, 2.0_f32).yx()`,  or 

`(1, 2, 3, 4).wzyx()` ), familiar to anyone who used GLSL, to tuples of up to 4 elements.

Just import the traits via `use tuple_swizzle::swizzle::*` 

Works for all types that implement Copy

