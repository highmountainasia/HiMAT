## Key Details

| | |
|:-----|:-----|
| Purpose of this file | Detail available ROMS model output from COAWST simulations and its temporal availability |
| Dataset generation status | Please see "coawst_readme.md" for details |
| Output data format | NetCDF |


## Variable Descriptions and Time Frequencies

| | | | | | |
|:-----|:-----|:-----|:-----|:-----|:-----|
| **ROMS Name** | **Description** | **Units** |  **6 hr** | **Daily** | **Monthly** |
| lat_psi | land mask for cross-staggered grid (0 = land, 1 = ocean ) | none | | | |
| lat_rho | land mask for unstaggered grid (0 = land, 1 = ocean ) | none | | | |
| lat_rho | land mask for u-staggered grid (0 = land, 1 = ocean ) | none | | | |
| lat_rho | land mask for v-staggered grid (0 = land, 1 = ocean ) | none | | | |
| lon_psi | land mask for cross-staggered grid (0 = land, 1 = ocean ) | E | | | |
| lon_rho | land mask for unstaggered grid (0 = land, 1 = ocean ) | E | | | |
| lon_rho | land mask for u-staggered grid (0 = land, 1 = ocean ) | none | | | |
| lon_rho | land mask for v-staggered grid (0 = land, 1 = ocean ) | none | | | |
| mask_psi | land mask for cross-staggered grid (0 = land, 1 = ocean ) | none | | | |
| mask_rho | land mask for unstaggered grid (0 = land, 1 = ocean ) | none | | | |
| mask_rho | land mask for u-staggered grid (0 = land, 1 = ocean ) | none | | | |
| mask_rho | land mask for v-staggered grid (0 = land, 1 = ocean ) | none | | | |
| ocean_time | time since ROMS model initialization | s | | | |
| salt | salinity | psu | X | X | X |
| temp | potential temperature | Celsius | X | X | X |
| u | u-momentum | m s<sup>-1</sup> | X | X | X |
| ubar | vertically integrated u-momentum | m s<sup>-1</sup> | X | X | X |
| v | v-momentum | m s<sup>-1</sup> | X | X | X |
| vbar | vertically integrated v-momentum | m s<sup>-1</sup> | X | X | X |
| w | upward sea velocity | m s<sup>-1</sup> | X | X | X |
| zeta | sea surface height | m | X | X | X |