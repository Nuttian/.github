# Nuttian

**A distribution built on [Apache NuttX](https://nuttx.apache.org/), with
packages that install with dpkg and apt.**

Nuttian runs ordinary binary packages on a NuttX kernel build: each program
is a process in its own address space, linked against NuttX's own C library
as `libc.so`. The same packages, from the same sources: 64-bit Arm today,
x86-64 and RISC-V 64 soon. The goal is the POSIX PSE54 profile.

- **Try it:** <https://nuttian.org/> and the
  [proof-of-concept releases](https://github.com/Nuttian/poc-releases)
  (QEMU images for macOS, Linux and Windows with WSL 2).
- **Packages:** <https://packages.nuttian.org/>: one sheet per package,
  with every change Nuttian makes for NuttX, and why.
- **Archive:** `https://archive.nuttian.org/` (apt).
- **Contact:** dev@nuttian.org; security issues: security@nuttian.org.

Nuttian works with the Apache NuttX community: fixes to NuttX go upstream.

<sub>Nuttian is not a project of the Apache Software Foundation. Apache,
Apache NuttX and NuttX are trademarks of The Apache Software
Foundation.</sub>
