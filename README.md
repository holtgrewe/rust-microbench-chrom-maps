# Rust Microbenchmark: Maps for chromosome names.

## How To Run

```
rustup run nightly cargo bench
```

## Results

```
   Compiling rust-microbench-chrom-maps v0.1.0 (/vol/local/projects/rust-microbench-chrom-maps)
    Finished bench [optimized] target(s) in 0.59s
     Running target/release/deps/rust_microbench_chrom_maps-3d231d6b1ead2ff2

running 6 tests
test bench_hashbrown        ... bench:     776,507 ns/iter (+/- 146,149)
test bench_hashbrown_short  ... bench:     626,686 ns/iter (+/- 24,966)
test bench_hashmap          ... bench:   1,616,228 ns/iter (+/- 80,735)
test bench_hashmap_short    ... bench:   1,484,405 ns/iter (+/- 57,363)
test bench_linear_map       ... bench:   6,991,546 ns/iter (+/- 209,180)
test bench_linear_map_short ... bench:   1,808,658 ns/iter (+/- 395,363)

test result: ok. 0 passed; 0 failed; 0 ignored; 6 measured; 0 filtered out
```