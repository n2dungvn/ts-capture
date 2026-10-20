FFmpeg corresponding source inputs for TS Capture 3.0.3

FFmpeg revision: 46d899d7a02bc63237472cc4897258d5ddf274ac
BtbN recipe revision: 63ac3265b0789ea16c7b1f8351cd2ad195a28722
Upstream Actions run: https://github.com/BtbN/FFmpeg-Builds/actions/runs/39250769506
Dependency source-cache artifact: 12185707025 (download-cache)
Binary ZIP SHA256: d1ff977a8026bf9841d5b2f4960825551fe306cdcf0f4d0de1e76f216459ae3a

Download all source parts, plus source-manifest.json and SHA256SUMS.txt.
Extract the parts into the same directory. Extract the FFmpeg and recipe ZIPs.
The inputs/*.tar.xz archives preserve the original upstream dependency sources
and submodules; licenses and notices are retained inside them. The recipe ZIP
includes patches, configure/build scripts and the reconstructed win64/gpl/8.1
Dockerfile. Its FF_CONFIGURE flags were compared with the shipped binary.

Build reference: the pinned BtbN README, build.sh, generate.sh, scripts.d,
images, variants and addins/8.1.sh. The upstream build uses Linux, Docker and
the MinGW cross toolchain. Place the hashed dependency archives under the
recipe's .cache/downloads directory. Pin FFmpeg to the revision above instead
of fetching the moving release branch. The generated Dockerfile records the
source archive hashes. Build tooling, upstream container availability and
external toolchains are separate prerequisites. A full rebuild was not run
as part of this preparation pass; bit-for-bit reproducibility is not claimed.

No changes were made to the FFmpeg or dependency source archives.
Generated recipe metadata: Dockerfile for win64/gpl/8.1.
Contact for source distribution issues: n2dungvn@gmail.com
GPLv3+ rights for FFmpeg and applicable rights for each dependency are retained.
The TS Capture app source is a separate work and is not part of these assets.
