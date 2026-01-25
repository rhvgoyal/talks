# Overlayfs filesystem architecture and SELinux support

**Event:** Vault 2017, Linux Storage and Filesystems Conference
**Location:** Cambridge, MA, USA  
**Date:** March 2017

## Abstract
Overlayfs is a relatively new filesystem which implements copy on write
semantics at the file level. It is specially gaining popularity in the
container world where container technologies like docker are using overlayfs
for image and container storage.

This talk plans to give an overview of overlayfs design, what are some of the
outstanding concerns and what is being done to address those upstream. It also
provides some details of how docker makes use of overlayfs and how it provided
some significant speed up w.r.t devicemapper. In the end the talk dives into
details of SELinux support recently added to overlayfs, what were some of the
challenges and how these were handled.

## Materials
- [Slides (PDF)](overlayfs-and-containers-presentation-valult-2017.pdf)

## Topics
Overlayfs filesystem, SELinux, Container Storage
