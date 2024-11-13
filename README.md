_(NOTE: This file is used as a template for the release descriptions at https://github.com/paintdotnet/release/releases)_

---

These are the offline installers, portable ZIPs, and deployment MSIs for Paint.NET. The web installer is also provided, which will download and run the correct installer for any supported CPU and OS.

**Release notes:** https://.../...

**System Requirements:**
- Windows 11, or Windows 10 v21H2, or Windows Server 2022
- 64-bit CPU (Intel/AMD x64 with AVX2, or ARM64)
- GPU with support for Direct3D 11, such as an NVIDIA GeForce, AMD Radeon, Intel Arc, Intel Iris (Plus or Xe), or Intel UHD
- SSD
- _Optional:_ A display that supports High Dynamic Range (HDR) or Wide Color Gamut (WCG)
- _Optional:_ A pen or drawing tablet that supports Windows Ink

**Notes about supported hardware:**
- Examples of CPUs with AVX2 include:
  - Intel Core 4th generation (Haswell, 2013) or newer
  - AMD Ryzen 1st generation (2017) or newer.
- For a list of GPUs that support Direct3D 11, see the "11_0" row in the table at https://en.wikipedia.org/wiki/Feature_levels_in_Direct3D
- For HDR and WCG displays, Paint.NET will be able to make use of the display's full color gamut and Windows will manage color accuracy and consistency. Images will not be clamped to sRGB's color gamut.
- For SDR displays, Paint.NET will operate in sRGB mode which means images will be clamped to sRGB's color gamut. This ensures consistent color reproduction, but color accuracy depends on the display itself being configured for sRGB as well.

**Notes about unsupported hardware:**
- Intel/AMD CPUs without AVX2 will work but will be slower. Our testing and optimization efforts no longer include Intel/AMD CPUs without AVX2.
- An HDD will work but will have slow performance and it is not supported. Our testing and optimization efforts no longer include HDDs.
- GPUs that do not support Direct3D 11 cannot be used, relegating those tasks to the CPU. Performance will be slower, and some effects may take an excruciatingly long time to render.

_(Friendly hint: If you don't know what an MSI is, then it's almost certainly not the download you want. Just grab the "anycpu" installer if you're not sure which one to use.)_

_The "source code" ZIP does not contain any actual files or source code, it is just included automatically as part of GitHub's "releases" functionality._
