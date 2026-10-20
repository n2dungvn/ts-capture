FFmpeg tool sources for TS Capture 3.0.3

Public release: https://github.com/n2dungvn/ts-capture/releases/tag/tools-3.0.3

The original two source ZIPs are distributed as 34 sequential binary segments.
This permits resumable parallel transfer without changing source ZIP contents.
The format is ordinary concatenation, not a proprietary archive format.

Download source-transfers.json to see every segment URL, byte size and SHA-256.
For each archive, download its listed segments, concatenate their bytes in the
listed order to obtain the ZIP filename, verify the ZIP hash, then extract it.
Extract both restored ZIPs into the same directory.

Optional helpers supplied on this release:
- Get-ToolSources.ps1: Windows PowerShell 5.1+ or PowerShell 7.
- get_tool_sources.py: Python 3 standard library, on Windows/macOS/Linux.
Review a helper before running it. It downloads only the public source segments,
verifies segment hashes, reconstructs both original ZIPs and checks their hashes.
No GitHub account or payment is required for these public source downloads.

The ZIP contents include FFmpeg source at revision
46d899d7a02bc63237472cc4897258d5ddf274ac and BtbN build recipes at revision
63ac3265b0789ea16c7b1f8351cd2ad195a28722, plus unchanged upstream dependency
source-cache archives. Their licenses and notices are retained. SOURCE-README.txt
inside the restored ZIPs contains the build reference and tool prerequisites.

The complete source archive SHA-256 values are in SHA256SUMS.txt and the full
source inventory is in source-manifest.json. The generated recipe configuration
matches the distributed binaries. A full rebuild was not performed and
bit-for-bit reproducibility is not claimed.

Source-distribution contact: n2dungvn@gmail.com