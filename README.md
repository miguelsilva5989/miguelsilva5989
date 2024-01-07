- 👋 Hi, I’m @miguelsilva5989
- 🧾 I've been working in IT since 2012 mostly as a Data Engineer/Business Intelligence consultant
- 👀 I’m interested in Python and Rust projects
- 🌱 I’m currently learning Rust

I am now developing my own meme 🙃 programming language (FPS Lang)[https://github.com/miguelsilva5989/fps-lang] take a look 😊

```rust
// this is FRAME 0
print("printed at frame 1 - declared at frame 0");
let a = 0;

#3 // frame 1 will be executed 3 times
print("printed at frames 2|3|4 - declared at frame 1");

for 0..=1 {
    print("printed at frames 2|3|4|5|6|7 - declared at frame 1 inside for loop"); 
    a = a + 1;
    print(a);
}

# // frame 4
print("printed at frame 5 - declared at frame 4");
print(a); // should print 4
##
```

output
```rust
FPS 1 -> printed at frame 1 - declared at frame 0
FPS 2 -> printed at frames 2|3|4 - declared at frame 1
FPS 2 -> printed at frames 2|3|4|5|6|7 - declared at frame 1 inside for loop
FPS 2 -> 1 // 'a' value - printed inside for loop
FPS 3 -> printed at frames 2|3|4 - declared at frame 1
FPS 3 -> printed at frames 2|3|4|5|6|7 - declared at frame 1 inside for loop
FPS 3 -> 2 // 'a' value - printed inside for loop
FPS 4 -> printed at frames 2|3|4 - declared at frame 1
FPS 4 -> printed at frames 2|3|4|5|6|7 - declared at frame 1 inside for loop
FPS 4 -> 3 // 'a' value - printed inside for loop
FPS 5 -> printed at frames 2|3|4|5|6|7 - declared at frame 1 inside for loop
FPS 5 -> 4 // 'a' value - printed inside for loop
FPS 5 -> printed at frame 5 - declared at frame 4
FPS 5 -> 4 // 'a' value - printed at frame 5 (declared at frame 4)
FPS 6 -> printed at frames 2|3|4|5|6|7 - declared at frame 1 inside for loop
FPS 6 -> 5 // 'a' value - printed inside for loop
FPS 7 -> printed at frames 2|3|4|5|6|7 - declared at frame 1 inside for loop
FPS 7 -> 6 // 'a' value - printed inside for loop
```


<!---
miguelsilva5989/miguelsilva5989 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
