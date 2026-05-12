# ForNaLab datasets

## Rationale

This repository contains the functionality to standardize several datasets of the [Forest & Nature Lab (ForNaLab)](https://www.ugent.be/bw/environment/en/research/fornalab) to [Darwin Core Occurrence](https://www.gbif.org/dataset-classes) datasets that can be harvested by [GBIF](http://www.gbif.org).

## Datasets

Title (and GitHub directory) | IPT | GBIF
--- | --- | ---
[DIGITAF_FLANDERS](https://github.com/inbo/fornalab-datasets/tree/main/datasets/digitaf_flanders) | [IPT](https://ipt.inbo.be/manage/resource?r=digitaf_flanders) | [GBIF](https://doi.org/10.15468/cm9c76)
[FORMICA_VEG](https://github.com/inbo/fornalab-datasets/tree/main/datasets/formica_veg) | [IPT](https://ipt.inbo.be/resource?r=formica_veg) | [GBIF](https://doi.org/10.15468/be9pwc)
[FORMICA_LEPIDOPTERA](https://github.com/inbo/fornalab-datasets/tree/main/datasets/formica_lepidoptera) | [IPT](https://ipt.inbo.be/resource?r=formica_lepidoptera) | [GBIF](https://doi.org/10.15468/3sckuk)

## Repo structure

The structure for each dataset in [datasets](datasets) is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── data
│   ├── raw                  : Source data, input for mapping script
│   └── processed            : Darwin Core output of mapping script GENERATED
│
└── src
    └── dwc_mapping.Rmd      : Darwin Core mapping script

```

## Contributors

[List of contributors](https://github.com/inbo/fornalab-datasets/graphs/contributors)

## License

[MIT License](LICENSE) for the code and documentation in this repository. The included data is released under another license.
