<h1 align="center">
  <img src="https://raw.githubusercontent.com/moongetsu/AniSmooth/main/AniSmooth/AniSmooth-Logo.png" height="48" alt="AniSmooth"/>
</h1>
<p align="center">
  <b>Model weight host for AniSmooth.</b><br>
  <i>Interpolation model weights, served as release assets.</i>
</p>

<p align="center">
  <a href="https://github.com/moongetsu/AniSmooth">AniSmooth Extension</a> ·
  <a href="#-interpolation">Interpolation</a> ·
  <a href="#-usage">Usage</a>
</p>

<hr>

This repository hosts the AI model weights for the [AniSmooth](https://github.com/moongetsu/AniSmooth) After Effects extension. Files are published as **release assets**, grouped by purpose into one release per category. The extension downloads what it needs automatically and verifies each file by SHA-256 before loading.

> [!NOTE]
> Weight files only, no code. A ✓ marks models AniSmooth uses today; the rest are mirrored for upcoming features. Original models belong to their respective authors.

**Download URL pattern:**

```
https://github.com/moongetsu/AniSmooth-Models/releases/download/interpolation/<filename>
```

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

## 📦 Usage

AniSmooth downloads these automatically, no manual step needed. Each file is verified against its SHA-256 before loading.

<details>
<summary>SHA-256 (models AniSmooth uses)</summary>

| File | SHA-256 |
| :-- | :-- |
| `rife425.pth` | `040ed973997570f4f85489be3d8eb64be9c0cffdf0a9f049443b6a4838ed88f1` |
| `rife425_heavy.pth` | `49f7c82d3866860683992042ba8eb559b9c01fbe2600b80a53c56de05bb13b6f` |

</details>

<details>
<summary>Manual install</summary>

Place a file at:

```
%APPDATA%\com.moongetsu.extensions\AniSmooth\backend\weights\<model-key>\<filename>
```

Example: `...\weights\rife425\rife425.pth`.

</details>
