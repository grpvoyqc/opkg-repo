# opkg-repo

opkg package feed for [tourguided](https://github.com/grpvoyqc/tourguide-server) — tour guide audio relay server for GL-MT3000.

## Usage

Add this feed on your GL-iNet router via the web admin:

- **Name**: `tourguided`
- **URL**: `https://grpvoyqc.github.io/opkg-repo/aarch64_cortex-a53`

Then install:

```sh
opkg update
opkg install tourguided
```

To update:

```sh
opkg update
opkg upgrade tourguided
```
