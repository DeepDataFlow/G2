# G2

Chip Design AI Platform

## Prerequisites

G2 itself can run on Linux Rocky 8 or later, in addition to Ubuntu. However,
the prebuilt OpenROAD binary shipped with G2 requires Ubuntu 22.04 or later
(it needs glibc 2.35+, which Rocky/RHEL 8 does not provide) — this is only a
requirement if you plan to run OpenROAD flows. G2 has been tested on Ubuntu
22.04, 24.04, and 25.04.

G2 relies on the following Linux command-line tools: `nproc`, `zcat`, `firefox`, `tcsh`, `gvim`, `tclsh`.

On Ubuntu, install them with:

```bash
sudo apt-get install -y coreutils gzip firefox tcsh vim-gtk3 tcl
```

