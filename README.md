# Cpp-Integration
sch: https://www.google.com/search?q=rust+use+c%2B%2B+library,
https://www.google.com/search?q=rust+c%2B%2B+interop

## Quote: from book: "Fullstack Rust", pg.9
>**Why not Rust**
>
>One area in which Rust might not be right is when interfacing with large C++ codebases. *It is possible to have C++ talk to C and then have C talk to Rust and vice versa. That is the approach you should take today* if possible. However, Rust does not have a stable ABI nor a stable memory model. Hence, it is not directly compatible with C++. You can incrementally replace parts of a system with Rust and you can build new parts in Rust, but plug-and-play interoperability with C++ is not a solved problem.
