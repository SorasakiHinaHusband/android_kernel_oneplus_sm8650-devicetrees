# 一加 SM8650 内核设备树 🌳

高通 SM8650（pineapple）平台一加机型的内核设备树（DTB/DTBO 源头），
一加 12（`waffle`）的 MikuUI 构建会用它。

## 谁在管这棵树

**SorasakiHinaHusband** —— 设备树写错的话，开机第一屏就会给你脸色看 🙃

## 分支

`Cinderella` —— MikuUI（Android 17 / BP2A）。

## 怎么用

被 `kernel/oneplus/sm8650` 通过 Android 内核构建流程吃掉
（`TARGET_KERNEL_SOURCE` / `BOARD_INCLUDE_DTB_IN_BOOTIMG`）。

```bash
source build/envsetup.sh
lunch miku_waffle-cp2a-user
mka dtboimage
```

## 许可证

除非文件里另有说明，否则按 GNU General Public License v2 授权。
