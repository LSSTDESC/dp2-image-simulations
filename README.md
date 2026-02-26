# dp2-image-simulations

Image simulations for shear calibration of DP2

- [seacliff](https://github.com/lsstdesc/seacliff) will provide GalSim
  modules for interfacing with Rubin DM products
- Galaxy models will come from forced photometry of COSMOS
  observations[^1]
- The Milky Way stellar population model will come from TRILEGAL[^2]
- Simulations will be of _cell coadds_ (not PIV at this time)
- Simulations will cover the full DP2 footprint
- Simulations will feature four shear configurations: positive/negative
  shear in both shear axes, centered at each cell

## environments

```bash
mamba create -f environments/conda.yaml
```


# Notes from previous discussions

- <https://docs.google.com/presentation/d/1u0q9oo2bn0DyKU_4XiScut-W5GC0-V_wKrJYWQuxBaw/edit?usp=sharing>
- <https://docs.google.com/presentation/d/1u0q9oo2bn0DyKU_4XiScut-W5GC0-V_wKrJYWQuxBaw/edit?usp=sharing>


[^1]: <https://doi.org/10.1093/mnras/stab3055>
[^2]: <https://doi.org/10.3847/1538-4365/ac7be6>
