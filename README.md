# AKI
Antergos Kernel Installer

## Official packages

#### linux
The Linux kernel and modules from the core repository. Vanilla kernel with a few patches applied.

#### linux-hardened
A security-focused Linux kernel applying a set of hardening patches to mitigate kernel and userspace exploits. It also enables more upstream kernel hardening features than linux along with user namespaces (with unprivileged usage disabled by default via a patch), audit and SELinux.

#### linux-lts
Long term support (LTS) Linux kernel and modules from the core repository.

#### linux-zen
The ZEN Kernel is the result of a collaborative effort of kernel hackers to provide the best Linux kernel possible for everyday systems.

## AUR packages

Note for AUR packages, "pre-compiled" means the packages are (usually) maintained, tested and verified to be working. Some of the listed packages may also be available as binary packages via Unofficial repositories.

#### linux-amd-staging-git
 Linux kernel with AMDGPU DC patches

#### linux-aufs_friendly
The aufs-compatible linux kernel and modules, useful when using docker.

#### linux-bfq
[BFQ](http://algo.ing.unimo.it/people/paolo/disk_sched/) is a proportional-share storage-I/O scheduler that also supports hierarchical scheduling with a cgroups interface.

#### linux-ck / linux-lts-ck
Linux Kernel built with Con Kolivas' ck1 patchset—see the #-ck section or the linux-ck page. Additional options which can be toggled on/off in the PKGBUILD include: BFQ scheduler, nconfig, localmodconfig and use running kernel's config.

#### linux-fbcondecor
The Linux Kernel and modules with fbcondecor support.

#### linux-git
Linux kernel and modules built using sources from Linus Torvalds' Git repository.

#### linux-ice
The Linux Kernel and modules with gentoo-sources patchset and TuxOnIce support.

#### linux-lqx
Liquorix is a distro kernel replacement built using a Debian-targeted configuration and the ZEN kernel sources. Designed for desktop, multimedia, and gaming workloads, it is often used as a Debian Linux performance replacement kernel. Damentz, the maintainer of the Liquorix patchset, is a developer for the ZEN patchset as well.

#### linux-macbook
The Linux kernel and modules with Macbook patches

#### linux-mainlineAUR
The Mainline Linux Kernel and modules.

#### linux-mptcp
The Linux Kernel and modules with Multipath TCP support.

#### linux-next-git
The Linux-next-git kernel and modules

#### linux-nvme
The Linux kernel with patches made by Andy Lutomirski. These patches enable NVME drives to enter lower power states.

#### linux-pae
PAE stands for P-hysical A-ddress E-xtension to access 4 GiB RAM on 32-bit systems. This is not needed for 64-bit systems.

#### linux-pf
Linux kernel and modules with the pf-kernel patch [-ck patchset (BFS included), TuxOnIce, BFQ] and aufs3.

#### linux-rt / linux-rt-lts
Linux kernel with the realtime patch set. Improves latency and introduces hard realtime support. (https://rt.wiki.kernel.org/)

#### linux-selinux
This kernel is mostly the same as the official Linux kernel with SELinux available, but not enabled. You have to enable it explicitly in the kernel command line for it to be enable by the kernel. Note that the official linux-hardened package now enables SELinux support alongside the kernel self-protection patches.

#### linux-surfacepro3
Linux kernel with patches for the surface pro3.

#### linux-usermode
User-Mode Linux is a safe, secure way of running Linux versions and Linux processes. Run buggy software, experiment with new Linux kernels or distributions, and poke around in the internals of Linux, all without risking your main Linux setup (http://user-mode-linux.sourceforge.net/)

#### linux-userns
The Linux-userns kernel and modules with CONFIG_USER_NS enabled (EXPERIMENTAL). This allows containers, i.e. vservers, to use user namespaces to provide different user info for different servers.

#### linux-vfio
The Linux kernel and a few patches written by Alex Williamson (acs override and i915) to enable the ability to do PCI Passthrough with KVM on some machines.

#### linux-zen-git
The ZEN Kernel is the result of a collaborative effort of kernel hackers to provide the best Linux kernel possible for everyday systems. (GIT version)
