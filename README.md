# Home Assistant Theme - Vastayan Bond (Light & Dark mode!)

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/hacs/integration)
[![donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://paypal.me/snakefist)

* [Preparation](#preparation)
* [HACS installation](#hacs_installation)
* [Manual installation](#manual_installation)
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
4. Restart Home Assistant

### <a name="manual_installation"></a>Manual installation
1. Copy the file `vastayan_bond.yaml` into your **themes** folder
3. Restart Home Assistant

### <a name="enable_the_theme"></a>Enable the theme
- Open your **Profile** in Home Assistant and select the theme called **Xayah**
- Alternatively activate it for the cards you want to redesign.


### <a name="samples"></a>Samples
To be added.
