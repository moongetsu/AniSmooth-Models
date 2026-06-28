<h1 align="center">
  <img src="https://raw.githubusercontent.com/moongetsu/AniSmooth/main/AniSmooth/AniSmooth-Logo.png" height="48" alt="AniSmooth"/>
</h1>
<p align="center">
  <b>Model weight host for AniSmooth.</b><br>
  <i>RIFE interpolation and ShuffleCUGAN / Adore / Fallin upscale models, served as release assets.</i>
</p>

<p align="center">
  <a href="https://github.com/moongetsu/AniSmooth">AniSmooth Extension</a> ·
  <a href="#-models">Models</a> ·
  <a href="#-usage">Usage</a>
</p>

<hr>

This repository stores the AI model weights used by the [AniSmooth](https://github.com/moongetsu/AniSmooth) After Effects extension. Files are published as **release assets** (tag `main`) and downloaded automatically by the extension on first use.

> [!NOTE]
> These are weight files only. There is no code here. For the extension itself, see the [AniSmooth repo](https://github.com/moongetsu/AniSmooth).

---

## 🧠 Models

All files live under the **`main`** release. Download URL pattern:

```
https://github.com/moongetsu/AniSmooth-Models/releases/download/main/<filename>
```

| Model Key | File | Size | Type |
| :-- | :-- | :-- | :-- |
| `rife4.25` | `rife425.pth` | ~22 MB | Frame interpolation |
| `rife4.25-heavy` | `rife425_heavy.pth` | ~87 MB | Frame interpolation |
| `adore` | `adore.pth` | ~5.7 MB | Upscaling |
| `fallin_soft` | `Fallin_soft.pth` | ~5.7 MB | Upscaling |
| `fallin_strong` | `Fallin_strong.pth` | ~5.7 MB | Upscaling |
| `shufflecugan` | `sudo_shuffle_cugan_9.584.969.pth` | ~5.7 MB | Upscaling |

<details>
<summary>SHA-256 checksums</summary>

| File | SHA-256 |
| :-- | :-- |
| `rife425.pth` | `040ed973997570f4f85489be3d8eb64be9c0cffdf0a9f049443b6a4838ed88f1` |
| `rife425_heavy.pth` | `49f7c82d3866860683992042ba8eb559b9c01fbe2600b80a53c56de05bb13b6f` |
| `adore.pth` | `443378bdc6db6cf4a75eea61ee7afc78b2c4b6a4d3b3981a40ff61f38bbc8f1a` |
| `Fallin_soft.pth` | `910aa56a9a1187df97c3284177da1bc66836679350b2613191340734937e9960` |
| `Fallin_strong.pth` | `14b8415199aa66a6507725408a66758ba2bff9286736f19f7f07524efd821a56` |
| `sudo_shuffle_cugan_9.584.969.pth` | `88a6d89f04eaf27a9f7b60937857768a6bc04fb360670bd9951ef533acab0616` |

</details>

---

## 📦 Usage

AniSmooth downloads these automatically, no manual step needed. The extension verifies each file against the SHA-256 above before loading.

<details>
<summary>Manual install</summary>

Place a file at:

```
%APPDATA%\com.moongetsu.extensions\AniSmooth\backend\weights\<model-key>\<filename>
```

Example: `...\weights\adore\adore.pth`.

</details>

---

## ⚠️ Notice

Weights are redistributed for use with AniSmooth. Original RIFE, ShuffleCUGAN, and related models belong to their respective authors.
