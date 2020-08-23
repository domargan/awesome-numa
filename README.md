# Awesome NUMA
A community-oriented list of libraries, tools, and resources aimed to assist with NUMA-aware software development.

[Non-Uniform Memory Access (NUMA)](https://en.wikipedia.org/wiki/Non-uniform_memory_access) refers to multiprocessor systems whose memory is divided into multiple memory nodes.

## Contributing
To add, remove or change things on the list:
[please submit a pull request to the GitHub repository](https://github.com/domargan/awesome-numa).

## NUMA Linux library bindings and interfaces
- [libnuma - The libnuma shared library to control NUMA policy for processes or shared memory on Linux](https://github.com/numactl/numactl)
- [numa-rs - Rust bindings for libnuma](https://github.com/cwpearson/numa-rs)
- [go-numa - Go bindings for libnuma](https://github.com/rakyll/go-numa)
- [jnuma - Java bindings for libnuma](https://github.com/xerial/jnuma)
- [py-numa - Python bindings for libnuma](https://github.com/smira/py-numa)
- [ocaml-numa - OCAML bindings for libnuma](https://github.com/stevebleazard/ocaml-numa)
- [libNumaAPI - A cross-platform API wrapper for NUMA technology](https://github.com/sergeyvfx/libNumaAPI)

## NUMA-aware memory placement and scheduling
- [numactl - A program to run other programs with a specific NUMA policy](https://github.com/numactl/numactl)
- [numatool - A wrapper to linux kernels `move_pages` system call to balance processes' pages across NUMA nodes](https://github.com/go2starr/numatool)
- [libtorque - A threaded, continuations-based I/O event library for manycore NUMA machines](https://github.com/dankamongmen/libtorque)
- [pgasus - A C++ parallel programming framework for NUMA systems, based on PGAS semantics](https://github.com/osmhpi/pgasus)
- [NUMASK - A skip list designed to exploit the characteristics of NUMA architectures to improve performance](https://github.com/sss-lehigh/numask)
- [golang-numa - A golang utility library for NUMA-aware code](https://github.com/lrita/numa)
- [NumaAllocator- A simple C++ header NUMA memory allocator](https://github.com/ReidAtcheson/numaallocator)
- [numanji - A rustlang Local-affinity first NUMA-aware allocator with optional fallback](https://github.com/bastion-rs/numanji)
- [Tesson -  A tool for NUMA-aware sharding with Docker](https://github.com/kobolog/tesson)
- [Umpire - An application-focused API for memory management on NUMA & GPU architectures ](https://github.com/LLNL/Umpire)

## Observation and profiling tools
- [numastat - A program display NUMA allocation statistics](https://github.com/numactl/numactl)
- [NUMACC - A golang-based tool to check CPU affinity and NUMA configuration for containers and pods](https://github.com/mJace/numacc)
- [NumaTOP - An observation tool for runtime memory locality characterization and analysis of processes and threads running on a NUMA system](https://github.com/intel/numatop)
- [SnuMAP - A NUMA performance profiler](https://github.com/SnuMAP/SnuMAP)
- [irqstat - A `/proc/interrupts` watcher designed for NUMA systems](https://github.com/lanceshelton/irqstat)
- [Numa-Trace - A Pin tool to track NUMA memory accesses](https://github.com/marksfu/Numa-Trace)
- [NUMAPROF - A NUMA memory profliler based on Pintool to track remote memory accesses](https://github.com/memtt/numaprof)
- [Numalize - A memory tracing tool to detect communication and page usage of NUMA applications](https://github.com/matthiasdiener/numalize)
- [NumaMMA - A lightweight NUMA memory profiler/analyzer and a NUMA application execution engine](https://github.com/numamma/numamma)
- [numap - A Linux library for memory profiling based on hardware performance monitoring unit (PMU](https://github.com/numap-library/numap)
- [pcm-numa - A tool to monitor local and remote memory accesses on a NUMA system](https://github.com/opcm/pcm)

## Benchmarking
- [Comm|Scope - A NUMA-aware multi-CPU multi-GPU CUDA data transfer benchmarks](https://github.com/c3sr/comm_scope)
- [Numafac - Scripts to calculate the NUMA factor of NUMA machines, based on the stream and lmbench3 benchmarks.](https://github.com/matthiasdiener/numafac)
- [nurdma - Understanding RDMA Behavior in NUMA Systems](https://github.com/sss-lehigh/nurdma)
- [numabench - A NUMA benchmarking tool](https://github.com/BrownBigData/numabench)
- [numa-bench - A NUMA-aware memory allocation benchmark](https://github.com/stephentu/numa-bench)

## NUMA-aware data structures
- [Skyhooks - An experimental NUMA-aware, lock-free heap memory allocator](https://github.com/ShisoftResearch/Skyhooks)
- [rw-numa-locks - A NUMA-aware reader-writer locks](https://github.com/azu-labs/rw-numa-locks)
- [NUMA_Black-Box - Black-box concurrent data structures for NUMA architectures](https://github.com/xqgex/NUMA_Black-Box)

## About
This list was compiled by [Domagoj Margan](https://github.com/domargan) with help and resources from the systems community.
