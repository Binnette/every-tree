# 🌳 Every Tree 🌲

A plugin for `Every Door` to contribute 🌳 **trees** in OpenStreetMap.

![Every Tree Logo](assets/every-tree-logo.png)

## ⭐ Features

### 👀 Quick survey of tree species

- Trees with known species are green
- Others are in brown

![Main](assets/main.png)

### 🍒 Commons tree species presets

The plugin provides a set of common tree species presets to help you tag tree species.

![Presets](assets/add-tree.png)

## 🛠️ How to create the plugin file

### Using bash

```bash
# Remove old files
rm -f every-tree.edp every-tree-micro.edp

# Create the classic plugin
zip -r every-tree.edp icons/ langs/ LICENSE plugin.yaml

# Create the micro version of the plugin
mkdir -p tmp-edp
cp -r icons langs LICENSE tmp-edp/
cp plugin-micro.yaml tmp-edp/plugin.yaml
(cd tmp-edp && zip -r ../every-tree-micro.edp .)
rm -rf tmp-edp
```

### Using PowerShell

```powershell
Compress-Archive -Path icons/*, langs/*, LICENSE, plugin.yaml, README.md -DestinationPath every-tree.edp
```

## 📥 How to install the plugin

📲 Scan this QR code with `Every Door` version **6 or later**:

![QR Code](assets/qr-code.png)

Or [⬇️ download the plugin here](https://raw.githubusercontent.com/Binnette/every-tree/refs/heads/main/every-tree.edp).

[🔍 More information on installation](https://every-door.app/plugins/install/).

### Install the micro version

![QR Code micro](assets/qr-code-micro.png)

## 📝 Todo list
- [ ] Ask all my questions to Ilya.
- [ ] Draw custom icons for each tree species.
- [ ] Add a second button for `natural=shrub` with plants :
    - "🍇 Blackberry" species="Rubus fruticosus"
    - "🔴 Raspberry" species="Rubus idaeus"
    - Juniperus communis
    - "Sambucus nigra"
    - "blueberry
    - "🌱 Strawberry" species="Fragaria vesca"