# Rust Notes

## Intro to Rust
### March 7, 2022

Hello World:
```
fn main() {
  let greeted = "Rust"
  println!("Hello, ()", greeted);
 }
 ```
   
 Some notes: 
 -Compile by using `rustc filename`
 -variables introducd with `let`
 
 Example function:
 ```
 fn gpa_for(grade: $str) -> f64 {
    match grade {
        "A" => 4.0,
        "B" => 3.0,
        "C" => 2.0,
        "D" => 1.0,
        "F" => 0.0
    }
}
```

where `match` acts as `switch`

**Rust uses snake case like gpa_for NOT camel case: GpaFor***


 
