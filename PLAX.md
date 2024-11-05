# Types

* Stage 0
  * Variable declaration needs to go on top of function
  * Signed integer: i8, i16, i32, i64
  * Unisnged integer: u8, u16, u32, u64
  * Floating: f32, f64
  * Stage 0 only - displacement to access array member/struct field

* Stage 1
  * Boolean
  * Array of a type
  * Struct
     * Union
     * Bitfield

* Stage 2
   * Number
   * Default parameter arguments
   * Classes
 
## Example: stage 1 to stage 0

Fibbonacci

Stage 0:
```
fn fib(n: u32) : u32 {
   if n < 2 { return 1; }
   return fib(n - 1) + fib(n - 2);
}
```

```

```

# Stage 0

```
(def (my_function a b c) ...)     # a, b, c are variables to be used on the block

```

# Stage 1
