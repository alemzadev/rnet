# rnet
Discovering Rust

Mac systems:
shell: 
>rustup target add x86_64-unknown-linux-musl
>brew install FiloSottile/musl-cross/musl-cross  
>cargo build --target=x86_64-unknown-linux-musl 

in file .cargo/config add following:
[target.x86_64-unknown-linux-musl]
linker = "x86_64-linux-musl-gcc"
