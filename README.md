# Home Assistant Theme - Vastayan Bond (Light & Dark mode!)

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/hacs/integration)
[![donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://paypal.me/snakefist)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/SnakeFist007/ha_vastayan_bond?label=Version&labelColor=grey&color=green)
![GitHub All Releases](https://img.shields.io/github/downloads/SnakeFist007/ha_vastayan_bond/total?&label=Total%20Downloads&labelColor=grey&color=green)

* [Preparation](#preparation)
* [HACS installation](#hacs_installation)
* [Manual installation](#manual_installation)
* [Font Installation](#font_installation)
* [Enable the theme](#enable_the_theme)
* [Samples](#samples)

### <a name="preparation"></a>Preparation
Check if **configuration.yaml** is loading the themes from the themes folder:   

<pre>
frontend:
  themes: !include_dir_merge_named themes
</pre>

If the **themes** folder does not exist in **config**, create one.   

### <a name="hacs_installation"></a>HACS installation
1. Open the Community Store (HACS)
2. Add `https://github.com/SnakeFist007/ha_vastayan_bond` as a custom repository
3. Install it
4. Go to config > lovelace dashboard > resources (config/lovelace/resources) and add this resource:
“/local/proxima-nova-font/ProximaNova-Regular.css” Resource type :stylesheet
5. Restart Home Assistant

### <a name="manual_installation"></a>Manual installation / Font installation
1. Copy the file `vastayan_bond.yaml` into your **themes** folder
2. Restart Home Assistant

---

### <a name="font_installation"></a>Font Installation
1. Copy the complete folder `proxima-nova-font` into your **www** folder
2. Go to **Configuration** > **Lovelace Dashboard** > **Resources** and add the following resource:

```
“/local/proxima-nova-font/ProximaNova-Regular.css” 
Resource type: stylesheet
```
3. Restart Home Assistant

If you want to use a different font and use this theme, you'll have to change the corresponding lines in the `vastayan_bond.yaml` file.

---

### <a name="enable_the_theme"></a>Enable the theme
- Open your **Profile** in Home Assistant and select the theme called **Vastayan Bond**
- Choose the mode you want to use it in! (Auto / Light / Dark)

---

### <a name="samples"></a>Samples
## Xayah Theme - Dark
<p align="center">
  <img src="https://i.imgur.com/7PrLhou.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/a4QPU3r.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/jV6XebU.png">
</p>

## Rakan Theme - Light
<p align="center">
  <img src="https://i.imgur.com/Dfc36SV.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/ksOdGp7.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/WhVqmBK.png">
</p>
