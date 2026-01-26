# Kdump, A Kexec-based Kernel Crash Dumping Mechanism

- **Event:** Ottawa Linux Symposium, 2005
- **Location:** Ottawa, Canada
- **Date:** July 2005
- **Published papers of the Linux Symposium:**
  [OLS 2005 Papers](https://www.kernel.org/doc/ols/2005/)

**Authors / Speakers:**  
- Vivek Goyal
- Eric W. Biederman
- Hariprasad Neelitheertha

## Abstract
Kdump is a kexec based kernel crash dumping mechanism, which is being
perceived as a reliable crash dumping solution for Linux. This paper begins
with brief description of what kexec is and what it can do in general case,
and then details how kexec has been modified to boot a new kernel even in a
system crash event.

Kexec enables booting into a new kernel while preserving the memory contents
in a crash scenario, and kdump uses this feature to capture the kernel crash
dump. Physical memory layout and processor state are encoded in ELF core
format, and these headers are stored in a reserved section of memory. Upon a
crash, new kernel boots up from reserved memory and provides a platform to
retrieve stored ELF headers and capture the crash dump. Also detailed are
ELF core header creation, dump capture mechanism, and how to configure and
use the kdump feature.

## Materials
- [Paper (PDF)](https://www.kernel.org/doc/ols/2005/ols2005v1-pages-177-188.pdf)
- [Slides (PDF)](ols-2005-kdump-prsentation-slides.pdf)

## Topics
Linux, Kdump, Kexec
