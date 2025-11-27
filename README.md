# SNES/SFC Maskrom Adapters

Adapters to replace SNES DIP32/DIP36 maskrom with PSOP44 Flash.

Maskroms: MX23C1601-12, M531610D-20, UPD23C4013 and other similar maskrom ICs.

![image](img/snes_maskrom_psop_to_dip_adapter_schematics.png)

## snes_maskrom_psop_to_dip_adapter
Backside PSOP44 to DIP36 adapter. Designed and tested for MX29F1610. Non destructive option, CE\`/OE\` pins of original maskrom should be cut.

![image](img/snes_maskrom_psop_to_dip_adapter_f.png) ![image](img/snes_maskrom_psop_to_dip_adapter_b.png)

![image](img/snes_maskrom_psop_to_dip_adapter.jpg)

## snes_maskrom_psop_to_dip_adapter_front
Fronside PSOP44 to DIP36 adapter. Designed and tested for MX29F1610. Replaces original maskrom.

![image](img/snes_maskrom_psop_to_dip_adapter_front_f.png) ![image](img/snes_maskrom_psop_to_dip_adapter_front_b.png)


Adapters to replace SNES PSOP36/PSOP42 maskrom with TSOP40/TSOP48 Flash.

Maskroms: MX23C1601-12, M531610D-20, UPD23C4013 and other similar maskrom ICs.

![image](img/snes_superfx_adapter_small_adapter_schematics.png)

## snes_maskrom_tsop_to_fx_adapter
Inspired by https://github.com/retrostage/SNES-SuperFX-adapter project.
Redesigned in KiCad to use less expensive production process, added some test points (WE#, RST#) for inschematic programming ability.

![image](img/snes_maskrom_tsop_to_fx_adapter_schematics.png)

![image](img/snes_maskrom_tsop_to_fx_adapter_f.png)
![image](img/snes_maskrom_tsop_to_fx_adapter_b.png)
![image](img/snes_maskrom_tsop_to_fx_adapter.png)