# InvenTree BOM

A KiCad plugin to push BOM information to InvenTree.

> **Note**
> This isn't currently packaged as a plugin, but it can be installed and run on a `.pcb_new` file by running a command like the following: `KiCad.app/Contents/Applications/pcbnew.app/Contents/Frameworks/Python.framework/Versions/Current/bin/python3 src/inventree_bom/inventree_bom_action.py myproject.kicad_pcb`
>
> A configuration file must also currently be created manually next to the `.kicad_pcb` file called `inventree-bom.config.ini`:
>
>     [inventree]
>     username=engineer
>     password=partsonly
>     server=https://demo.inventree.org