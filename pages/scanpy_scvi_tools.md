# Single-cell data analysis with Scanpy and scvi-tools

A flourishing body of computational tools have made it easier to robustly analyze single-cell -omics datasets in a scalable and reproducible way.
Here we will dive into conducting an analysis of a single-cell RNA-sequencing dataset with [Scanpy](https://scanpy.readthedocs.io/en/stable/) and [scvi-tools](https://scvi-tools.org),
two popular Python libraries for general purpose analysis tasks.

This tutorial will cover the following items:

1. Overview of the [AnnData](https://anndata.readthedocs.io/en/latest/) format, which powers Python-based single-cell libraries
2. Data preprocessing and quality control
3. Dimensionality reduction and dataset integration
4. Differential expression
5. Visualization

There will be a focus not only on how to run the software, but also the motivation behind each of these steps.

## Notebook

The colab notebook can be found [here](https://colab.research.google.com/drive/1V4BD3SAGDwLzvMUn90FMOHYVNG_iP4Ee?usp=sharing). The full notebook can also be viewed in a web browser [here](/assets/scvi_notebook.html).

## Relevant references

- Lopez, R., Regier, J., Cole, M. B., Jordan, M. I., & Yosef, N. (2018). Deep generative modeling for single-cell transcriptomics. Nature methods, 15(12), 1053-1058.
- Luecken, M. D., & Theis, F. J. (2019). Current best practices in single‐cell RNA‐seq analysis: a tutorial. Molecular systems biology, 15(6), e8746.
- Wolf, F. A., Angerer, P., & Theis, F. J. (2018). SCANPY: large-scale single-cell gene expression data analysis. Genome biology, 19(1), 15.

