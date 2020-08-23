# Awesome NUMA
A community-oriented list of libraries, tools, and resources aimed to assist with NUMA-aware software development.

[Non-Uniform Memory Access (NUMA)](https://en.wikipedia.org/wiki/Non-uniform_memory_access) refers to multiprocessor systems whose memory is divided into multiple memory nodes.

## Contributing
To add, remove or change things on the list:
[please submit a pull request to the GitHub repository](https://github.com/domargan/awesome-numa).

## NUMA library bindings and interfaces
- [libnuma](https://github.com/numactl/numactl) - The libnuma shared library to control NUMA policy for processes or shared memory on Linux
  - [numa-rs](https://github.com/cwpearson/numa-rs) - Rust bindings for libnuma
  - [go-numa](https://github.com/rakyll/go-numa) - Go bindings for libnuma
  - [jnuma](https://github.com/xerial/jnuma) - Java bindings for libnuma
  - [py-numa](https://github.com/smira/py-numa) - Python bindings for libnuma
  - [ocaml-numa](https://github.com/stevebleazard/ocaml-numa) - OCAML bindings for libnuma
- [libNumaAPI](https://github.com/sergeyvfx/libNumaAPI) - A cross-platform API wrapper for NUMA architecture
- [hwloc](https://github.com/open-mpi/hwloc) - A portable API to detect and exploit the topology of parallel architectures
- [Windows NUMA API](https://docs.microsoft.com/en-us/windows/win32/procthread/numa-support) - Official Microsoft Win32 NUMA API

## NUMA-aware memory placement and scheduling
- [numactl](https://github.com/numactl/numactl) - A program to run other programs with a specific NUMA policy
- [numatool](https://github.com/go2starr/numatool) - A wrapper to linux kernels `move_pages` system call to balance processes' pages across NUMA nodes
- [libtorque](https://github.com/dankamongmen/libtorque) - A threaded, continuations-based I/O event library for manycore NUMA machines
- [pgasus](https://github.com/osmhpi/pgasus) - A C++ parallel programming framework for NUMA systems, based on PGAS semantics
- [NUMASK](https://github.com/sss-lehigh/numask) - A skip list designed to exploit the characteristics of NUMA architectures to improve performance
- [golang-numa](https://github.com/lrita/numa) - A golang utility library for NUMA-aware code
- [NumaAllocator](https://github.com/ReidAtcheson/numaallocator) - A simple C++ header NUMA memory allocator
- [numanji](https://github.com/bastion-rs/numanji) - A rustlang Local-affinity first NUMA-aware allocator with optional fallback
- [Tesson](https://github.com/kobolog/tesson) -  A tool for NUMA-aware sharding with Docker
- [Umpire](https://github.com/LLNL/Umpire) - An application-focused API for memory management on NUMA & GPU architectures

## Observation and profiling tools
- [numastat](https://github.com/numactl/numactl) - A program display NUMA allocation statistics
- [NUMACC](https://github.com/mJace/numacc) - A golang-based tool to check CPU affinity and NUMA configuration for containers and pods
- [NumaTOP](https://github.com/intel/numatop) - An observation tool for runtime memory locality characterization and analysis of processes and threads running on a NUMA system
- [SnuMAP](https://github.com/SnuMAP/SnuMAP) - A NUMA performance profiler
- [irqstat](https://github.com/lanceshelton/irqstat) - A `/proc/interrupts` watcher designed for NUMA systems
- [Numa-Trace](https://github.com/marksfu/Numa-Trace) - A Pin tool to track NUMA memory accesses
- [NUMAPROF](https://github.com/memtt/numaprof) - A NUMA memory profliler based on Pintool to track remote memory accesses
- [Numalize](https://github.com/matthiasdiener/numalize) - A memory tracing tool to detect communication and page usage of NUMA applications
- [NumaMMA](https://github.com/numamma/numamma) - A lightweight NUMA memory profiler/analyzer and a NUMA application execution engin
- [numap](https://github.com/numap-library/numap) - A Linux library for memory profiling based on hardware performance monitoring unit
- [pcm-numa](https://github.com/opcm/pcm)- A tool to monitor local and remote memory accesses on a NUMA system

## Benchmarking
- [Comm|Scope](https://github.com/c3sr/comm_scope) - A NUMA-aware multi-CPU multi-GPU CUDA data transfer benchmarks
- [Numafac](https://github.com/matthiasdiener/numafac) - Scripts to calculate the NUMA factor of NUMA machines, based on the stream and lmbench3 benchmarks
- [nurdma](https://github.com/sss-lehigh/nurdma) - Understanding RDMA behavior in NUMA systems
- [numabench](https://github.com/BrownBigData/numabench) - A NUMA benchmarking tool
- [numa-bench](https://github.com/stephentu/numa-bench) - A NUMA-aware memory allocation benchmark

## NUMA-aware data structures
- [Skyhooks](https://github.com/ShisoftResearch/Skyhooks) - An experimental NUMA-aware, lock-free heap memory allocator
- [rw-numa-locks](https://github.com/azu-labs/rw-numa-locks) - A NUMA-aware reader-writer locks
- [NUMA_Black-Box](https://github.com/xqgex/NUMA_Black-Box) - Black-box concurrent data structures for NUMA architectures

## About
This list was compiled by [Domagoj Margan](https://github.com/domargan) with help and resources from the systems community.
