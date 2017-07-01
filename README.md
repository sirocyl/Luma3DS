# Lumina
*An idiot-proof, safe(r) minimal 3DS bootstrapper.*

**_Who?_** Lumina is forked from Luma3DS, with modifications by sirocyl. See https://github.com/AuroraWright/Luma3DS/wiki/Credits

**_What?_** **Lumina** is based on [Luma3DS](https://github.com/AuroraWright/Luma3DS/), the popular CFW of choice for the Nintendo 3DS.  
While Luma3DS adds a lot of features, and I would recommend that you use it instead, Lumina aims to do the bare minimum that a 3DS bootstrapper and firmware patcher should do.  

**_Why?_** For fun. I'm just trimming away at Luma3DS until the very core features present themselves, and nothing else. It allows you to run unauthorized ("homebrew") content by removing signature checks, as well as [protecting FIRM](https://github.com/AuroraWright/Luma3DS/wiki/Other-features-and-notes#boot9strap-and-firm-write-protection) from being overwritten by a System Update, and everything in the [Standard Features](https://github.com/AuroraWright/Luma3DS/wiki/Other-features-and-notes#standard-features) of Luma3DS proper.

**_How?_** To use it, you will need a console capable of running homebrew software on the ARM9 processor. We recommend [Plailect's guide](https://3ds.guide/) for details on how to get your system ready.
Compilation instructions are identical to [Luma3DS.](https://github.com/AuroraWright/Luma3DS/blob/master/README.md#compiling)

Lumina does **not** support EmuNAND, payload chainloading, splash screens, exception handlers, or many of the accomodations made for EmuNAND and other features.

While based on Luma3DS v8.0, it does **not** include Rosalina, or the GDB stub.

**If you're wondering if you should use this bootstrapper, __don't;__ use [Luma3DS](https://github.com/AuroraWright/Luma3DS/releases/) instead!**

## Licensing

This software is licensed under the terms of the GPLv3.  
You can find a copy of the license in the LICENSE.txt file.
