<!-- SPDX-FileCopyrightText: 2026 Progmasoft <support@progmasoft.com> -->
<!-- SPDX-License-Identifier: MIT -->

# OpenTalaLoader

OpenTalaLoader is the bootloader of [OpenTala](https://github.com/Progmasoft/opentala). It runs only on UEFI firmware,
on amd64 and AArch64, and loads the Mach-O kernel, the kernel extensions it needs at boot, and the initial file system.

Secure Boot is optional; the loader is signed with keys that Progmasoft manages.

It is written in GNU99 under the
[Progmasoft Core C Coding Guidelines](https://github.com/Progmasoft/progmasoft-cpp) and built with BSD Make.

No code is written yet.

## License

[MIT](LICENSE.txt), also covered by the [Progmasoft Patent Grant 1.1](PATENTS.md). Participation follows the
[Code of Conduct](CODE_OF_CONDUCT.md).
