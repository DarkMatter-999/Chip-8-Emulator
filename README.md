# Chip8 Emulator

Chip8 is a simple virtual machine. It is an interpreted programming language developed to make programming games easier on the 8-bit computers of the 1970-80s

## Usage
```bash
cargo run --release ./<path-to-roms>/<game>
```

Some Chip8 Roms/Games can be downloaded from [here](https://www.zophar.net/pdroms/chip8/chip-8-games-pack.html).

## Demo
![Demo running space inavders](/assets/demo.png)

### Project Structure
- `c8_core` emulator core library
    - `src`
        - `lib.rs` core emulator functionality
- `src`     main gui directory
    - `main.rs` defines GUI through SDL2