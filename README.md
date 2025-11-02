# HypergraphPercol K=2 Implementation

## Overview
This repository accompanies the paper *Generalization of Single-Linkage with Higher-Order Interactions* and provides the implementation of the HypergraphPercol algorithm for the special case of triangle connectivity ($K=2$). The current implementation is delivered as a Google Colab notebook that demonstrates the full experimental workflow described in the article.

## Colab notebook
The complete, executable workflow is available as a Colab notebook:
- [HypergraphPercol\_K2 Colab notebook](https://colab.research.google.com/drive/10W8x9R39QYX-4PgKdiMO21MpX86uGX33?usp=sharing)

## Benchmark datasets
The notebook evaluates the method on two public benchmarks:
- **Olive-oil dataset** (Wickham et al., 2011), accessible *via* this repositpry: [oliveoil.rda](https://github.com/Ayana-Inria/HypergraphPercol_K2/oliveoil.rda) or as part of the `pgmm` package in the R datasets repository: [olive.csv](https://github.com/vincentarelbundock/Rdatasets/blob/master/csv/pgmm/olive.csv).
- **SIPU clustering benchmarks**, available through the Clustbench Python package (Gagolewski, 2022): [ClustBench project page](https://clust-bench.readthedocs.io/).

Please refer to the notebook for detailed instructions on downloading and preprocessing each dataset before running the algorithm.

## Citation
If you use the code in this repository, please cite it:

> Louis Hauseux (2025). *HypergraphPercol K2: Reference implementation for K=2 higher-order Single-Linkage*. https://github.com/Ayana-Inria/HypergraphPercol_K2, gitHub repository.

Or the corresponding article:

> Louis Hauseux, Konstantin Avrachenkov & Josiane Zerubia (2025+). *Generalization of Single-Linkage with Higher-Order Interactions.*

## License
- Source code and executable content: licensed under the [GNU General Public License v3.0-only](https://www.gnu.org/licenses/gpl-3.0.html).
- Textual documentation (including this README): shared under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) with an additional restriction forbidding commercial use.

By using this repository you agree to comply with both licensing terms.
