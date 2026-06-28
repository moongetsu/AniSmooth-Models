<h1 align="center">
  <img src="https://raw.githubusercontent.com/moongetsu/AniSmooth/main/AniSmooth/AniSmooth-Logo.png" height="48" alt="AniSmooth"/>
</h1>
<p align="center">
  <b>Model weight host for AniSmooth.</b><br>
  <i>Interpolation, upscaling, and restoration model weights, served as release assets.</i>
</p>

<p align="center">
  <a href="https://github.com/moongetsu/AniSmooth">AniSmooth Extension</a> ·
  <a href="#-interpolation">Interpolation</a> ·
  <a href="#-upscale">Upscale</a> ·
  <a href="#-restore--denoise">Restore</a> ·
  <a href="#-usage">Usage</a>
</p>

<hr>

This repository hosts the AI model weights for the [AniSmooth](https://github.com/moongetsu/AniSmooth) After Effects extension. Files are published as **release assets**, grouped by purpose into one release per category. The extension downloads what it needs automatically and verifies each file by SHA-256 before loading.

> [!NOTE]
> Weight files only, no code. A ✓ marks models AniSmooth uses today; the rest are mirrored for upcoming features. See [CREDITS.md](CREDITS.md) for model authors and sources.

**Download URL pattern:**

```
https://github.com/moongetsu/AniSmooth-Models/releases/download/<category>/<filename>
```

`<category>` is `interpolation`, `upscale`, or `restore`.

---

## 🎞 Interpolation

Release tag: **`interpolation`** (RIFE and VFI models).

| File | Size | Used |
| :-- | --: | :-: |
| `rife425.pth` | 21.7 MB | ✓ |
| `rife425_heavy.pth` | 82.7 MB | ✓ |
| `rife425_lite.pth` | 21.5 MB | |
| `rife422.pth` | 35.6 MB | |
| `rife422_lite.pth` | 18.6 MB | |
| `rife421.pth` | 35.6 MB | |
| `rife420.pth` | 58.7 MB | |
| `rife418.pth` | 20.5 MB | |
| `rife417.pth` | 20.5 MB | |
| `rife417_lite.pth` | 10.0 MB | |
| `rife416_lite.pth` | 10.0 MB | |
| `rife415.pth` | 20.5 MB | |
| `rife415_lite.pth` | 10.0 MB | |
| `rife414.pth` | 20.5 MB | |
| `rife413_lite.pth` | 10.1 MB | |
| `rife46.pth` | 20.3 MB | |
| `rife_elexor.pth` | 20.4 MB | |
| `pervfi.pth` | 33.4 MB | |

---

## 🔍 Upscale

Release tag: **`upscale`** (anime and video upscalers).

| File | Size | Used |
| :-- | --: | :-: |
| `adore.pth` | 5.4 MB | ✓ |
| `Fallin_soft.pth` | 5.4 MB | ✓ |
| `Fallin_strong.pth` | 5.4 MB | ✓ |
| `sudo_shuffle_cugan_9.584.969.pth` | 5.4 MB | ✓ |
| `AnimeSR_v2.pth` | 5.7 MB | |
| `2x_ModernSpanimationV2.pth` | 8.5 MB | |
| `2x_ModernSpanimationV1.5.pth` | 15.1 MB | |
| `2x_ModernSpanimationV1.pth` | 15.1 MB | |
| `2x_AnimeJaNai_HD_V3_Sharp1_Compact_430k.pth` | 4.6 MB | |
| `2x_AnimeJaNai_HD_V3_Sharp1_UltraCompact_425k.pth` | 2.3 MB | |
| `2x_AnimeJaNai_HD_V3Sharp1_SuperUltraCompact_25k.pth` | 0.4 MB | |
| `2x_AniScale2S_Compact_i8_60K.pth` | 2.3 MB | |
| `2x_OpenProteus_Compact_i2_70K.pth` | 2.3 MB | |
| `2x_umzi_anime_rtmosr.pth` | 11.6 MB | |
| `2x_umzi_anime_rtmosr_net.pth` | 11.6 MB | |
| `2x_enhancr_da_figsr.pth` | 7.9 MB | |
| `2x_enhancr_da_smosr_v1.safetensors` | 21.0 MB | |
| `2x_Gauss.safetensors` | 1.0 MB | |
| `4x_APISR_RRDB_GAN_generator.pth` | 51.4 MB | |
| `RealESRGAN_x2plus.pth` | 63.9 MB | |
| `Saryn-V1-Lite.pth` | 10.9 MB | |
| `1x-AnimeUndeint-Compact.pth` | 4.6 MB | |

---

## 🧹 Restore & Denoise

Release tag: **`restore`** (deblock, dehalo, denoise, fixers).

| File | Size | Used |
| :-- | --: | :-: |
| `1x_Anime1080Fixer_SuperUltraCompact.pth` | 0.1 MB | |
| `1x_HurrDeblur_SuperUltraCompact.pth` | 0.4 MB | |
| `1x_DeHalo_v1_Compact.pth` | 4.6 MB | |
| `1x_DeH264_SPAN.safetensors` | 9.9 MB | |
| `1xDeH264_realplksr.pth` | 28.2 MB | |
| `1xDeJPG_realplksr_otf.pth` | 28.2 MB | |
| `scunet_color_real_psnr.pth` | 68.6 MB | |
| `drunet_deblocking_color.pth` | 124.5 MB | |
| `1x_umzi_adc_gater3_v1.safetensors` | 155.5 MB | |
| `NAFNet-GoPro-width64.pth` | 259.2 MB | |

---

## 📦 Usage

AniSmooth downloads these automatically, no manual step needed. Each file is verified against its SHA-256 before loading.

<details>
<summary>SHA-256 (models AniSmooth uses)</summary>

| File | SHA-256 |
| :-- | :-- |
| `rife425.pth` | `040ed973997570f4f85489be3d8eb64be9c0cffdf0a9f049443b6a4838ed88f1` |
| `rife425_heavy.pth` | `49f7c82d3866860683992042ba8eb559b9c01fbe2600b80a53c56de05bb13b6f` |
| `adore.pth` | `443378bdc6db6cf4a75eea61ee7afc78b2c4b6a4d3b3981a40ff61f38bbc8f1a` |
| `Fallin_soft.pth` | `910aa56a9a1187df97c3284177da1bc66836679350b2613191340734937e9960` |
| `Fallin_strong.pth` | `14b8415199aa66a6507725408a66758ba2bff9286736f19f7f07524efd821a56` |
| `sudo_shuffle_cugan_9.584.969.pth` | `88a6d89f04eaf27a9f7b60937857768a6bc04fb360670bd9951ef533acab0616` |

</details>

<details>
<summary>Manual install</summary>

Place a file at:

```
%APPDATA%\com.moongetsu.extensions\AniSmooth\backend\weights\<model-key>\<filename>
```

Example: `...\weights\adore\adore.pth`.

</details>
