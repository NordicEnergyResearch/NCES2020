# ON-TIMES for NCES2020

This is the repository of the open-source ON-TIMES energy system model developed by [EML](https://energymodellinglab.com), IVL (https://www.ivl.se/) and VTT (https://www.vttresearch.com/en) as part of the Nordic Clean Energy Scenarios project conducted by [NER](https://www.nordicenergy.org/).


## Short description

The model includes all of the five nordic countries (Denmark, Finland, Island, Norway and Sweden)

The ON-TIMES model is build on the structures of the NER SHIFT project (https://www.nordicenergy.org/flagship/project-shift/), the TIMES-DK model (https://www.esymodels.man.dtu.dk/times-dk & https://doi.org/10.1016/j.esr.2018.11.003) and TIMES models developed by VTT by adding the countries Finland and Island, an endogenous trade matrix of energy commodities, CCUS module, an updated SubRES dataset and updated GPD projections, taxes and subsisidies, delivery costs, renewable and fossil fuel potentials. As well as added excess heat potentials and data center development based on the TIMES-DK model and expanded the datacenter represrentation to Island, Norway and Sweden. Furthermore, the model were used with a soft-link to a Balmorel model (developed by https://www.ea-energianalyse.dk/da/forside/). Files for this link is included to determine power interconnectors, prices to neithbouring countries and exports of hydrogen. 

The ON-TIMES model is based on the [TIMES model generator](https://iea-etsap.org/index.php/etsap-tools/model-generators/times).

On-TIMES: Open Nordic - The Integrated Market Allocation EFOM System

The ON-TIMES model version v1.final was run in [VEDA2.0](https://iea-etsap.org/index.php/etsap-tools/data-handling-shells/veda) using the CPLEX solver.

## Key contributers to the model strucuture 

- E4SMA
- DTU Sustainability
- Danish energy agency 
- IVL
- VTT
- EML

## Results viewer

The scenario results calculated with [ON-TIMES v1.final](https://github.com/NordicEnergyResearch/NCES2020/releases/tag/v1.final) can be viewed here:
> [https://cleanenergyscenarios.nordicenergy.org/](https://cleanenergyscenarios.nordicenergy.org/)

## Contact to the developers

[EML](mailto:eml@energymodellinglab.com)


## License

Published under the Open Data Commons Open Database License (ODbL) v1.0.
