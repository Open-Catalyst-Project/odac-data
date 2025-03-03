# REPO DEPRECATION: In 2024 the FAIR Chemistry team consolidated its various resources to improve release/testing/availability, and [ODAC moved to the fairchem repo](https://github.com/FAIR-Chem/fairchem/tree/main/src/fairchem/data/odac). You can find updated documentation on how to use the consolidated resources at https://fair-chem.github.io/


# ODAC23 Dataset

To download the ODAC23 dataset, please see the links here: [ODAC23 Dataset](https://github.com/FAIR-Chem/fairchem/blob/main/docs/core/datasets/odac.md)

Pre-trained ML models and configs are available in the OCP repo: [ODAC23 Models](https://github.com/FAIR-Chem/fairchem/blob/main/docs/core/model_checkpoints.md#open-direct-air-capture-2023-odac23)

This repository contains the list of [promising MOFs](https://github.com/Open-Catalyst-Project/odac-data/tree/main/promising_mof) discovered in the ODAC23 paper, as well as details of the [classifical force field calculations](https://github.com/Open-Catalyst-Project/odac-data/tree/main/force_field). 

Information about supercells can be found in [supercell_info.csv](https://github.com/Open-Catalyst-Project/odac-data/tree/main/supercell_info.csv) for each example.

## Citing

Please consider citing the following paper in any research manuscript using the ODAC23 dataset:

```bibtex
@article{odac23_dataset,
    author = {Anuroop Sriram and Sihoon Choi and Xiaohan Yu and Logan M. Brabson and Abhishek Das and Zachary Ulissi and Matt Uyttendaele and Andrew J. Medford and David S. Sholl},
    title = {The Open DAC 2023 Dataset and Challenges for Sorbent Discovery in Direct Air Capture},
    year = {2023},
    journal={arXiv preprint arXiv:2311.00341},
}
