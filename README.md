# FlurrySort™

[![FlurrySort™](https://repository-images.githubusercontent.com/1161503819/f7f6844d-5514-41a3-8077-883e6453dc52)](https://github.com/ghostproxies/flurrysort)

## Table of Contents

- [Introduction](README.md?tab=readme-ov-file#introduction)
- [Author](README.md?tab=readme-ov-file#author)
- [License](README.md?tab=readme-ov-file#license)
- [Reference](README.md?tab=readme-ov-file#reference)
- [Speed](README.md?tab=readme-ov-file#speed)

## Introduction

FlurrySort™ is the efficient sorting algorithm for arbitrary input.

It's intended to replace unstable sorting algorithms for practical use cases when the requirement is [hyper-fast speed](README.md?tab=readme-ov-file#speed).

Furthermore, it has [simple implementation](README.md?tab=readme-ov-file#reference), no auxiliary subarrays and no vendor-specific SIMD.

## Author

FlurrySort™ was created by [William Stafford Parsons](https://github.com/williamstaffordparsons) as a product of [GhostProxies](https://ghostproxies.com).

## License

FlurrySort™ is licensed with the [BSD-3-Clause](LICENSE) license.

## Reference

FlurrySort™ was implemented in C with operations that are simple to port to a majority of programming languages.

[flurrysort.c](flurrysort.c)

The `flurrysort` function sorts (in ascending order) an array of elements in place without preserving the relative order of equal elements.

`elements_length` must be the count of elements in the `elements` array.

The integral type of `element` must match the integral type of each element in the `elements` array.

## Speed

FlurrySort™ was benchmarked and refined extensively during development with varying 64-bit architectures, compilers, compiler optimization settings, devices, programming languages and sorting scenarios.

Specific benchmark results and time complexity details (using an AMD A4-9120C with `gcc -O3`) are coming soon.
