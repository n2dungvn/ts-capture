# TS Capture — privacy, licenses and tool sources

Publisher / Nhà phát hành: **Nguyễn Ngọc Dũng**  
Contact / Liên hệ: **n2dungvn@gmail.com**

## Privacy / Quyền riêng tư

- [Tiếng Việt](https://n2dungvn.github.io/ts-capture/privacy-vi.html)
- [English](https://n2dungvn.github.io/ts-capture/privacy-en.html)

## Third-party software / Thành phần bên thứ ba

- [Giấy phép và nguồn — Tiếng Việt](https://n2dungvn.github.io/ts-capture/licenses-vi.html)
- [Licenses and sources — English](https://n2dungvn.github.io/ts-capture/licenses-en.html)
- [Full license texts](third-party-licenses.txt)
- [SHA-256 source manifest](source-manifest.json)
- [Build/source directions](SOURCE-README.txt)

The `tools-3.0.3` release contains numbered segments of two tool-source ZIPs.
Download the segments and concatenate them in the order specified in
`source-transfers.json` to restore the original ZIPs. Optional PowerShell and
Python helpers on the release page download, verify and join the segments.
Extract both restored ZIPs into the same folder. They contain the original FFmpeg
and dependency sources plus pinned build scripts/patches for the binaries
bundled with TS Capture 3.0.3. No sign-in or payment is required to access the
public source downloads. Each component retains its applicable license.

The application code is maintained separately. This repository distributes
privacy documentation, third-party notices and upstream tool-source archives.
The source release is not a claim of codec patent clearance or trademark
endorsement. See the individual notices and source directions for scope.

[Download tool sources and assembly helpers](https://github.com/n2dungvn/ts-capture/releases/tag/tools-3.0.3)
