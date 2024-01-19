# rust-crc32

Calculate CRC-32 checksum for binary data.

## How to install

```sh
cargo add crc32_light
```

## How to use

```rs
use crc32_light::crc32;
fn main() {
    let crc = crc32(b"dog");
    println!("CRC32 = 0x{:08x}", crc);
}
```

