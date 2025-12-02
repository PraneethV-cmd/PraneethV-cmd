```rust
pub struct Praneeth {
    pub alias: String,
    pub status: String,
    pub languages: Vec<String>,
}

impl Praneeth {
    pub fn new() -> Self {
        Self {
            alias: "PraneethV-cmd".to_string(),
            status: "@AVV'26, CSE".to_string(),
            link: "bananameatpatty.vercel.app".to_string(),
            languages: vec![
                "C++".to_string(),
                "Python".to_string(),
                "Go".to_string(),
                "Haskell".to_string(),
                "rust".to_string(),
            ],
        }
    }

    pub fn now(&self) {
        prtinln!("Locked in and geeked up!");
    }
}
```
