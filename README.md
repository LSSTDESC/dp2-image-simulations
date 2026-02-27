# dp2-image-simulations

- [imSim](https://github.com/LSSTDESC/imSim) provides GalSim modules for
  simulating the Rubin observatory telescope and survey
- [seacliff](https://github.com/lsstdesc/seacliff) will provide GalSim
  modules for interfacing with Rubin DM products


## from PVI

- Goal is to test the DM pipelines for shear calibration
- Galaxy models will be morphologically simple

## from coadd

- Goal is to calibrate astrophysical effects, including the impact of
  blending on the effective redshift distribution for lensing
- Galaxy models will come from forced photometry of COSMOS
  observations[^1]
- The Milky Way stellar population model will come from TRILEGAL[^2]
- Simulations will cover the full DP2 footprint
- Simulations will feature four shear configurations: positive/negative
  shear in both shear axes, centered at each cell


## environments

```bash
mamba create -f environments/conda.yaml
```

## configs

```bash
galsim configs/simple.yaml
```

# Notes from previous discussions

- <https://docs.google.com/document/d/1sgeUwVdgq2OOlqe_OtPmwLn2D4RuV6gqI4Q2K29heVA/edit?usp=sharing>
- <https://docs.google.com/document/d/1sfHn0SKkr-rPUeX8d4_WJ3xp41yfdu6KeR-tx8kz2gw/edit?usp=sharing>
- <https://docs.google.com/presentation/d/1u0q9oo2bn0DyKU_4XiScut-W5GC0-V_wKrJYWQuxBaw/edit?usp=sharing>


[^1]: <https://doi.org/10.1093/mnras/stab3055>
[^2]: <https://doi.org/10.3847/1538-4365/ac7be6>
