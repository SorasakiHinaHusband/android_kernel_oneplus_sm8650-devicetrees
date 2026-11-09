# OnePlus SM8650 device trees

Kernel device trees (DTB/DTBO sources) for OnePlus devices based on Qualcomm
SM8650 (pineapple), used by the OnePlus 12 (`waffle`) MikuUI build.

## Maintainer

- **SorasakiHinaHusband** — <https://github.com/SorasakiHinaHusband>

## Branch

- `Cinderella` — MikuUI (Android 17 / BP2A)

## Usage

Consumed by `kernel/oneplus/sm8650` through the Android kernel build
(`TARGET_KERNEL_SOURCE` / `BOARD_INCLUDE_DTB_IN_BOOTIMG`).

```bash
source build/envsetup.sh
lunch miku_waffle-cp2a-user
mka dtboimage
```

## License

Licensed under the GNU General Public License, version 2, unless stated
otherwise in the individual source files.
