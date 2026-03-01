# Software-External-Dependencies

We host the following mirrors in case the original download link is offline

| Filename                        | sha256                                                           | Original source                                                      |
|---------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------|
| nanopb-0.3.9.4-linux-x86.tar.gz | e98dd6403ab8c5b271d32a6bc025e7e596bb181c7bc7e0492c5daa21fc44c940 | https://jpa.kapsi.fi/nanopb/download/nanopb-0.3.9.4-linux-x86.tar.gz |

## 85-brltty.rules
The BRLTTY service provides access to a console screen for blind people via a braille screen.

One of the udev rules conflicts with the device id used by our E-stops. Instead, we offer alternate udev rules to prevent this conflict.

## Toolchains
We have custom toolchains to cross-compile for the Raspbery Pi 5.

NOTE: the .config-for-aarch64 uses "aarch64-buildtohost-linux-gnu" as the host tuple. This can change depending on what the build -> host cross compilation toolchain's vendor string is.

| Filename | sha256 |
|----------|--------|
| aarch64-tbots-linux-gnu-for-x86.tar.xz | c6dfe4f1d85f2d42cf33a3259873223d137c9f2f14102d912ea9e3f8fa1d04c2 |
| aarch64-tbots-linux-gnu-for-aarch64.tar.xz | 924544f85e64050aa6fe02b15f26922ca656165a80fe8a3656a4da7d18419dd1 |
