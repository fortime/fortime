```rust
#[derive(Debug)]
struct Person<'twothousandandtwenty> {
    tag: Vec<&'twothousandandtwenty str>,
    interests: Vec<&'twothousandandtwenty str>,
    wish: &'twothousandandtwenty str,
}

fn main() {
    let me = Person {
        tag: vec!["Vimer", "Archer"],
        interests: vec!["Linux", "Web Novel"],
        wish: "A 🦀 job",
    };  
    println!("{:?}", me);
}
```

<!--
**fortime/fortime** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
