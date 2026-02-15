<div align="center">

# luci-theme-solo

<img src="https://raw.githubusercontent.com/SoloExodia/luci-theme-solo/master/luasrc/img/logo-solowrt.png">

Custom LuCI theme for SoloWRT firmware - Dark blue/black base with neon cyan accents

</div>

## Features

- 🎨 **Dark blue/black base** with neon cyan accents
- 👁️ **Sung Jinwoo background** - intense blue eyes theme
- ⚡ **Glowing logo** with cyan drop-shadow effects
- 📱 **Responsive** - separate mobile logo
- 🎨 **Custom color palette** extracted from SoloWRT branding
- 💫 **Smooth animations** and hover effects

## Installation

### Method 1: Via SoloWRT Builder

This theme is included in SoloWRT firmware builds. Simply flash the firmware.

### Method 2: Manual Installation

```bash
cd /tmp
git clone https://github.com/SoloExodia/luci-theme-solo.git
cd luci-theme-solo
cp -r luasrc/* /usr/lib/lua/luci/
cp -r root/* /
cp -r template/* /usr/lib/lua/luci/view/themes/solo/
```

Then go to System → System → Language and Style → Design → choose SoloWRT → Save & Apply.

## Screenshots

<p>

![Login Page](ss1.png)

![Dashboard](ss2.png)

![Network Settings](ss3.png)

![Mobile View 1](mobileview1.png)

![Mobile View 2](mobileview2.png)

![Mobile View 3](mobileview3.png)

</p>

## Credits

© SoloExodia 2024-2026

Based on luci-theme-alpha 4.0.0-beta by derisamedia, with extensive customization for SoloWRT branding.

## License

Apache-2.0 License
