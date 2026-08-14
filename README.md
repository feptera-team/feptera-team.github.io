# FepTera

<p align="center">
  <img src="FepTera.png" alt="FepTera logo" width="220" />
</p>

> **Software with a reason.**

FepTera is a student-led software group focused on practical tools for **Linux, Android, and Windows**. We publish work as it becomes real: clear release information, known limitations, and the details needed to evaluate a build before using it.

| Project | Focus | Current status |
| --- | --- | --- |
| **FepTera Linux** | A focused Debian-based developer operating system | FepTera Linux 1.0 amd64 release prepared |
| **ALLES** | A Linux-first AI project, named for the German word for “everything” | GUI work in progress |
| **Applications** | Small utilities for real-world problems across Linux, Android, and Windows | In development |

## FepTera Linux

The first FepTera Linux release is built around a Debian base, GNOME, GDM3, and GRUB boot support. It is designed as a developer-oriented workstation with practical development tooling and documented release evidence.

| Release detail | Value |
| --- | --- |
| Version | FepTera Linux 1.0 |
| Architecture | amd64 (Intel/AMD 64-bit) |
| Approximate size | 3.1 GB |
| SHA-256 | `42df0f9370b922911477e85926f2db82b91e11b20f82177df42f558c1a961ce6` |

The live project site will host release information, checksum instructions, and verified mirror links:

**https://feptera-team.github.io/**

## Verify a download

Always compare the ISO hash against the published SHA-256 value before installing:

```bash
sha256sum FepTera-Linux-1.0-amd64.iso
```

The command output must exactly match the hash above. Do not install an ISO whose checksum differs.

## Website

This repository serves the public FepTera website through GitHub Pages. It contains the production static bundle for the root site; the full application and release-catalog workflow are maintained separately.

## Contact

For project contact, write to **feptera.team@gmail.com**.

---

Copyright © 2026 FepTera. Release materials and included software may have their own licenses; consult each release’s accompanying documentation before redistribution.
