# rust-module-system

See [Clear explanation of Rust’s module system](https://www.sheshbabu.com/posts/rust-module-system/).

## Summary


* The module system is explicit - there’s no 1:1 mapping with file system
* We declare a file as module in its parent, not in itself
* The mod keyword is used to declare submodules
* We need to explicitly declare functions, structs etc as public so they can be consumed in other modules
* The pub keyword makes things public
* The use keyword is used to shorten the module path
* We don’t need to explicitly declare 3rd party modules


