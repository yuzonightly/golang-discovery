# golang-discovery

rust-lang/rustlings, but with `a few modifications :)`

Simple exercises in Go.

Maybe this repository will become a place I can use to explore various Go libraries.

_Tested on Linux. Does not run on Windows._

## Run

```bash
cargo run -- --help
cargo run -- file <file_name> # runs the specified file
cargo run -- dir <folder_name> # runs files located under the specified directory
cargo run -- --all # runs all files
```

### Example

```bash
cargo run -- file variables1 # runs variables1.go
cargo run -- dir variables # runs files located under the folder variables
```
