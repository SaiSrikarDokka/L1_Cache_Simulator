# L1 Cache Simulator

A simple L1 cache simulator written in C++.

## Build

Compile the source using your preferred C++ compiler. For example:

```bash
g++ main.cpp src/Block.cpp src/L1Cache.cpp -Iinc -o cache_simulator.exe
```

## Usage

Run the simulator with the following command-line arguments:

```bash
./cache_simulator.exe <cache_size> <memory_size> <associativity> <block_size> <trace_file>
```

### Example

```bash
./cache_simulator.exe 64 640 2 1 tracefile_blender.txt
```

## Trace files

Sample trace files are included in the repository:

- `tracefile_blender.txt`
- `tracefile_cactus.txt`
- `tracefile_namd.txt`

## Notes

Adjust the arguments to match your cache configuration and trace file.
