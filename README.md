<h1 align="center">
  <img src="https://raw.githubusercontent.com/moongetsu/AniSmooth/main/AniSmooth/AniSmooth-Logo.png" height="48" alt="AniSmooth"/>
</h1>
<p align="center">
  <b>Model weight host for AniSmooth.</b><br>
  <i>Restore & denoise model weights, served as release assets.</i>
</p>

<p align="center">
  <a href="https://github.com/moongetsu/AniSmooth">AniSmooth Extension</a> ·
  <a href="#-restore--denoise">Restore</a> ·
  <a href="#-usage">Usage</a>
</p>

<hr>

This repository hosts the AI model weights for the [AniSmooth](https://github.com/moongetsu/AniSmooth) After Effects extension. Files are published as **release assets**, grouped by purpose into one release per category. The extension downloads what it needs automatically and verifies each file by SHA-256 before loading.

> [!NOTE]
> Weight files only, no code. A ✓ marks models AniSmooth uses today; the rest are mirrored for upcoming features. See [CREDITS.md](https://github.com/moongetsu/AniSmooth-Models/blob/main/CREDITS.md) for model authors and sources.

**Download URL pattern:**

```
https://github.com/moongetsu/AniSmooth-Models/releases/download/restore/<filename>
```

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
<summary>Manual install</summary>

Place a file at:

```
%APPDATA%\com.moongetsu.extensions\AniSmooth\backend\weights\<model-key>\<filename>
```

Example: `...\weights\1x_Anime1080Fixer_SuperUltraCompact\1x_Anime1080Fixer_SuperUltraCompact.pth`.

</details>
