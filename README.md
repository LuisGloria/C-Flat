![alt text](https://github.com/LuisGloria/C-Flat/blob/main/C%E2%99%AD.png)

# C-Flat
C♭: For when C is too sharp

Welcome to **C♭**, an experimental programming language inspired by C, C++, and C# with a focus on simplifying syntax, enhancing memory management, and providing powerful concurrency features. 

## Why C♭?

C♭ is designed for developers who appreciate the power and control of C but want the higher-level abstractions of languages like C# without the verbosity and complexity of C++. It’s a project for learning, experimentation, and seeing how we can flatten some of the rough edges of low-level languages.

## Keep in mind

There is already a C-flat programming language but it involves music notes and it is an esoteric programming language.<br/>
You can see his project [here](https://github.com/NicksterSand/Cflat).

I do not claim the name of the language.<br/>
This is just something to help people learn C, C++ or C# without having to deal with memory managment and other complex stuff.<br/>

## Features
- **Simplified Syntax**: A blend of C and modern, high-level languages to keep things concise and readable.<br/>
- **Memory Management**: Optional garbage collection with the ability to manually manage memory if needed.<br/>
- **Concurrency Built-in**: Easy-to-use concurrency features like `async`/`await` for managing multi-threaded tasks.<br/>
- **Cross-Platform**: Designed with portability in mind, targeting desktop, server, and embedded systems.<br/>

## Example Code

Here’s a sneak peek of what C♭ code might look like:

```cflat
module main;

fn main() {
    println("Hello, World!");

    var result = add(5, 10);
    println("The result is: " + result);
}

fn add(int a, int b) -> int {
    return a + b;
}
```

# Instructions

Assuming you have LLVM installed, you can use the clang or llc tool to compile the LLVM IR file (output.ll) into an executable. Here’s how:

Compile LLVM IR to Object File:<br/>
```llc -filetype=obj output.ll -o output.o```<br/>

Link Object File to Create Executable:<br/>
```clang output.o -o output```<br/>

Run the Executable:<br/>
```./output```<br/>


# Notes

I don't even know if I'm gonna keep creating this, this probably doesn't even work.<br/>
Fell free to do whatever the f[BEEP] you want with it.
