# Extracting disease–gene associations from DISEASES

[DISEASES](http://diseases.jensenlab.org/Search) is a resource that integrates disease–gene associations across several channels of evidence [[ref](http://doi.org/10.1016/j.ymeth.2014.11.020 "Pletscher-Frankild et al (2015) DISEASES: Text mining and data integration of disease–gene associations")]. We're [using the resource](http://doi.org/10.15363/thinklab.d106 "Thinklab discussion: Processing the DISEASES resource for disease–gene relationships") in Rephetio, our network for drug repurposing. This repository extracts associations for the diseases and genes used in Rephetio.

[`diseases.ipynb`](diseases.ipynb) performs the conversion and processing and outputs user-friendly TSVs to [`data`](data).

## License

DISEASES content and derivatives are licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/ "Creative Commons Attribution 4.0 International"). All original content is licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/ "CC0 1.0 Universal: Public Domain Dedication").
