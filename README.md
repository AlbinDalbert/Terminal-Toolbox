# TermTools
Tools for making a simple and good looking terminal interface.
Design primarily for programs with multiple sub-programs.

## About
The Idea with this library is to have a easy to use framework to easily make terminal programs with multiple sub-programs. 
A way to make the text and color for the prints to make sense for the particular part of the program.

## Use It
To use this crate. Under the dependencies in your Cargo.toml, just add this crate as followed
```term_tools = { git = "https://github.com/AlbinDalbert/TermTools.git" }```
Then just update your cargo the everything is up and running.

## Road-map
This is still in a very early stage, a lot of things have not been implemented and/or works yet.

- [x]    Customizable for each instance of a `System` and `Program`
- [x]    Program inherits optional attributes from `System` by default
- [ ]    Programs can be executed via the `run()` function, (e.g. They are fundamentally linked together, not just for looks)