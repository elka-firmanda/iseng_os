# WORKING IN PROGRESS

```
rustup component add rust-src --toolchain nightly
```

```
rustup component add llvm-tools-preview --toolchain nightly
```

```
cargo install bootimage
```

```
cargo +nightly bootimage
```

```
qemu-system-x86_64 -drive format=raw,file=target/my_os/debug/bootimage-my_os.bin
```
