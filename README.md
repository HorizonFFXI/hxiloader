# hxiloader
FFXI Server Emulator Boot Loader
Based on the updated LSB bootloader.

This bootloader does log mac addresses in order to improve server security and track cheaters.

This bootloader does comply with GDPR as per Art. 4 mac addresses are only machine identifiers rather than personally identifiable information (PII).

This link explains the implications of GDPR and its application to this bootloader: https://gdpr-info.eu/art-4-gdpr/#:~:text=%E2%80%98pseudonymisation%E2%80%99%20means%20the,identifiable%20natural%20person%3B
```sh
mkdir build
cmake -S . -B build -A Win32
cmake --build build
```

## Release notes

### Windows

Requires VC2022 redist, included in https://aka.ms/vs/17/release/vc_redist.x86.exe

### Linux (through Wine)

Requires `winetricks vcrun2022`
