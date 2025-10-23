Hi, I'm Andrew

A developer with an obsession for learning. 

```rust
#[derive(Debug)]
enum TypingPreference {
    Static { peace_of_mind: u8 },
    Dynamic { runtime_terror: u8 },
}

#[derive(Debug)]
struct Developer {
    name: String,
    prefers: TypingPreference,
    escaped_from: String,
    motto: String,
}

// About Me
fn main() {
    let developer = Developer {
        name: String::from("Andrew Cooksey"),
        prefers: TypingPreference::Static { peace_of_mind: 100 },
        escaped_from: String::from("JavaScript runtime errors"),
        motto: String::from("Compiler errors > Runtime surprises"),
    };
    
    println!("{:?}", developer);
}
```

## Let's Connect
* [Email](mailto:andrewcooksey42@gmail.com)
