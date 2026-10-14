---
layout: default
title: CK-DOS Support
---

# CK-DOS

Explore retro PC software in a native Mac workspace, with an optional built-in
DOS environment and configurable PC hardware emulation.

## The CK-DOS 4.0 kernel and other operating systems

The custom **CK-DOS 4.0 kernel** is designed for fast execution and low
conventional-memory overhead. It includes DOS commands and tools built from
the MIT-licensed MS-DOS 4.0 sources.

A demonstrated 640 KB conventional-memory configuration leaves **about 616 KB**
as the largest executable program block. With simpler graphics profiles, enabling **Reclaim video memory** can free
additional memory: a demonstrated CGA configuration provides **736 KB** of
conventional memory and **about 712 KB** as the largest executable block.
These are examples; available memory depends on graphics settings, loaded
tools and software requirements. Here, 1 KB means 1,024 bytes.

You can also bypass the internal DOS kernel and boot your own installation
media using the emulated CPU, BIOS, disks and other PC hardware. This allows
installation of compatible versions of **Windows, OS/2 and other PC operating
systems**. Supply your own application files, operating-system media and any
required licenses. Compatibility depends on the particular version, software
and hardware configuration.

## Graphics, 3D and sound

Choose **Text only, Hercules, CGA, MCGA, VGA, SVGA (VESA), Tseng ET4000,
S3 Trio64, S3 86C928, Tseng ET4000/W32p, ATI Mach32 or Cirrus Logic GD5428**.
An optional **IBM 8514/A** companion accelerator is available alongside VGA.
These display profiles and 8514/A are included in Free.

First-generation **3dfx Voodoo Graphics** provides optional 3D support for
compatible software and guest drivers. It requires a Pentium CPU profile,
so it is available with Pro or the active Pro trial in the App Store edition.
It uses the existing Pro upgrade. Driver and game compatibility must be tested.

Free sound includes **PC speaker, AdLib OPL2/OPL3 FM, Sound Blaster 2,
Sound Blaster Pro 2 and Sound Blaster 16** profiles. “Pro 2” is a sound-card
name; basic digital/FM sound does not require the CK-DOS Pro purchase.
**Pro adds General MIDI through MPU-401**, using the bundled GM sound bank
or the macOS system synthesizer, including MIDI on the Sound Blaster 16 profile.

## Networking included in Free

The optional **ISA NE2000** adapter supports an in-app Ethernet segment between
sessions in the same application process, or **outbound IPv4 Internet/LAN
access through NAT**. Install the appropriate guest driver and network software.
Networking is disabled in new profiles and changes require a session restart.

The optional **web compatibility proxy** helps compatible legacy browsers
connect to HTTPS sites. It does not add modern web-page rendering capabilities
to an old browser. NAT provides outgoing connections; it does not expose an
inbound server or bridge the guest directly onto your physical LAN.

## Support

For support or privacy questions, email
[christian.klukas@gmail.com](mailto:christian.klukas@gmail.com).

Please include:

- CK-DOS version and macOS version
- CPU profile and relevant settings
- Steps to reproduce the problem, what you expected and what happened
- Adapter model and connection settings for COM-port issues
- A screenshot or performance report, if useful

Review files before sharing them. Performance reports contain information
about the Mac and its audio/display environment. Do not send passwords,
private files, license keys or third-party installation media.

## Free and Pro

CK-DOS Free includes basic CPU profiles through 486, ordinary display,
keyboard and audio support, access to selected application files and saved
sessions.

The optional **CK-DOS Pro** upgrade adds Pentium CPU profiles, DOS printing,
General MIDI and physical COM-port connections through supported adapters.
Pro is a permanent, one-time in-app purchase. The US storefront price is
**US$9.99**; the App Store shows the price for your storefront before purchase.

### Why should I try Pro first?

The free **7-day trial** lets you check your applications, MIDI, printing and
COM-port adapter before buying. We encourage you to use it because compatibility
depends on your software, configuration and connected devices.

The trial starts when you activate it, lasts **168 hours**, and never charges
you automatically. Afterwards, continue using Free or choose the permanent
Pro purchase. Starting the free trial and buying Pro are separate actions;
you do not need to buy Pro to activate the trial.

### What performance can I expect?

Pro expands CPU and peripheral compatibility; emulation speed depends on your
Mac, software and current workload. Approximately **486-class speed** has been
observed on an Apple M1 Mac. Newer Mac processors may achieve higher speeds,
but performance for particular software is not guaranteed.

The free performance check estimates what your current Mac and environment
can sustain. A warning, unfinished check or skipped check does not prevent
you from buying Pro. Test your own programs during the trial as well.

### How do I restore a purchase?

Open **CK-DOS → CK-DOS Pro…**, then choose **Restore Purchases**. Apple handles
purchases and authentication. Restoring a trial preserves its original start
date; it does not begin a new trial. CK-DOS itself requires no app account.

### What happens to my work when the trial ends?

Free remains available. Pro settings can be retained, but starting a new Pro
session or restoring a Pro session requires an active trial or permanent Pro
purchase. An already admitted session can finish. Existing generated files
and saved printer output remain recoverable; expiry does not delete your work.

### Will future updates cost extra?

App updates, error corrections and improvements to features you already own
are free. Genuinely new, separate features may be optional additional purchases.

## Files, devices and networking

Select only the files, folders, printers and adapters needed for your workflow.
CK-DOS saves profiles and session information locally. Hardware and program
compatibility should be tested before making a purchase decision.

Guest networking is optional and disabled in a new profile. Enabling outbound
networking lets guest software communicate with destinations you choose. The
optional web compatibility proxy processes guest web traffic locally and
makes HTTPS connections to selected sites. Those sites have their own privacy
practices.

Read the full [Privacy Policy](./privacy.html).

_Last updated: October 14, 2026_
