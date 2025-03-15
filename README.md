# Software-External-Dependencies

We host the following mirrors in case the original download link is offline

| Filename                        | sha256                                                           | Original source                                                      |
|---------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------|
| nanopb-0.3.9.4-linux-x86.tar.gz | e98dd6403ab8c5b271d32a6bc025e7e596bb181c7bc7e0492c5daa21fc44c940 | https://jpa.kapsi.fi/nanopb/download/nanopb-0.3.9.4-linux-x86.tar.gz |

## 85-brltty.rules
The BRLTTY service provides access to a console screen for blind people via a braille screen.

One of the udev rules conflicts with the device id used by our E-stops. Instead, we offer alternate udev rules to prevent this conflict.

## Toolchains
We have custom toolchains to cross-compile for the Jetson Nano and Raspbery Pi 5.

| Filename | sha256 |
|----------|--------|
| aarch64-tbots-linux-gnu-for-x86.tar.xz | 44f65b4d76028ef4e9c3f5cce8249dee60219844dca671278ca78f8aa5fd0726 |
| aarch64-tbots-linux-gnu-for-aarch64.tar.xz | 94181b1742ee72e0d1f8f0b80b9f602da6e7455b8fdc11a1690a55a5aff46cb3 |
