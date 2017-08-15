# akiu
Antergos Kernel Install Utility

## Official packages

### linux
    The Linux kernel and modules from the core repository. Vanilla kernel with a few patches applied.

### linux-hardened
    A security-focused Linux kernel applying a set of hardening patches to mitigate kernel and userspace exploits. It also enables more upstream kernel hardening features than linux along with user namespaces (with unprivileged usage disabled by default via a patch), audit and SELinux.

### linux-lts
    Long term support (LTS) Linux kernel and modules from the core repository.

### linux-zen
    The ZEN Kernel is the result of a collaborative effort of kernel hackers to provide the best Linux kernel possible for everyday systems.

## AUR packages

Note for AUR packages, "pre-compiled" means the packages are (usually) maintained, tested and verified to be working. Some of the listed packages may also be available as binary packages via Unofficial repositories.

### linux-aufs_friendlyAUR
    The aufs-compatible linux kernel and modules, useful when using docker.

### linux-ckAUR
    Linux Kernel built with Con Kolivas' ck1 patchset—see the #-ck section or the linux-ck page. Additional options which can be toggled on/off in the PKGBUILD include: BFQ scheduler, nconfig, localmodconfig and use running kernel's config.

### linux-fbcondecorAUR
    The Linux Kernel and modules with fbcondecor support. 

### linux-gitAUR
    Linux kernel and modules built using sources from Linus Torvalds' Git repository.

### linux-iceAUR
    The Linux Kernel and modules with gentoo-sources patchset and TuxOnIce support.

### linux-lqx
    Liquorix is a distro kernel replacement built using a Debian-targeted configuration and the ZEN kernel sources. Designed for desktop, multimedia, and gaming workloads, it is often used as a Debian Linux performance replacement kernel. Damentz, the maintainer of the Liquorix patchset, is a developer for the ZEN patchset as well.

linux-lts310AUR
    The Linux 3.10 Long-Term Support Kernel and modules.

linux-mainlineAUR
    The Mainline Linux Kernel and modules.

linux-mptcpAUR
    The Linux Kernel and modules with Multipath TCP support.

linux-pfAUR
    Linux kernel and modules with the pf-kernel patch [-ck patchset (BFS included), TuxOnIce, BFQ] and aufs3.

linux-rtAUR
    Linux kernel with the realtime patch set. Improves latency and introduces hard realtime support. https://rt.wiki.kernel.org/

linux-tresorAUR[broken link: package not found]/linux-lts-tresorAUR
    The current/LTS Linux Kernel and modules with integrated TRESOR

linux-vfioAUR/linux-vfio-ltsAUR
    The Linux kernel and a few patches written by Alex Williamson (acs override and i915) to enable the ability to do PCI Passthrough with KVM on some machines.

linux-kpatchAUR
    The Linux kernel with live patching support.
