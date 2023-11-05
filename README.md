# Software-External-Dependencies

We host the following mirrors in case the original download link is offline

| Filename                        | sha256                                                           | Original source                                                      |
|---------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------|
| nanopb-0.3.9.4-linux-x86.tar.gz | e98dd6403ab8c5b271d32a6bc025e7e596bb181c7bc7e0492c5daa21fc44c940 | https://jpa.kapsi.fi/nanopb/download/nanopb-0.3.9.4-linux-x86.tar.gz |

## 85-brltty.rules
The BRLTTY service provides access to a console screen for blind people via a braille screen.

One of the udev rules conflicts with the device id used by our E-stops. Instead, we offer alternate udev rules to prevent this conflict.
