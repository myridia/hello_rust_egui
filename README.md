# Example of Rust Egui

## Requirments
```
apt-get install git wget 
```

## List all targets you can compile to
```
rustup target list 


## Enable Zig 
check the last zig https://ziglang.org/download/
```
wget https://ziglang.org/builds/zig-linux-x86_64-0.14.0-dev.3385+055969b10.tar.xz
tar -xvf zig*.tar.xz
rm *.xz
mv zig-* zig
export PATH=$PATH:$(pwd)/zig
```
