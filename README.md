#  ESICUP Cutting & Packing Datasets
This repository contains a collection of datasets for academic research in Cutting and Packing (C&P) problems, maintained by the ESICUP community.
The datasets are intended to facilitate benchmarking and comparison of different algorithms and approaches.

<img width="280" height="206" alt="EWG_ESICUP" src="https://github.com/user-attachments/assets/235edec8-6119-415f-b50a-1cad54b31395" />

> [!NOTE]
> This resource was previously hosted at https://www.euro-online.org/websites/esicup/data-sets/, but has been migrated to GitHub in an effort to improve maintainability and long-term availability.

## Structure

The datasets are organized into subdirectories based on the dimensionality and type of the cutting and packing problems they address. 
Each subdirectory contains a README file that provides information about the datasets, including their source, characteristics, and any relevant references.


The main subdirectories are:
- [`1d`](1d/README.md): Datasets for one-dimensional cutting and packing problems.
- [`2d_rectangular`](2d_rectangular/README.md): Datasets for two-dimensional rectangular cutting and packing problems.
- [`2d_irregular`](2d_irregular/README.md): Datasets for two-dimensional irregular cutting and packing problems.
- [`3d_rectangular`](3d_rectangular/README.md): Datasets for three-dimensional rectangular cutting and packing problems.
- [`3d_irregular`](3d_irregular/README.md): Datasets for three-dimensional irregular cutting and packing problems.
- [`misc`](misc/README.md): Miscellaneous datasets that do not fit into the above categories.


## Contribute

As this is a community-driven resource, contributions are welcome!
To contribute, please [fork this repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo), make your changes, and [submit a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) for review.

We encourage contributions in the following areas:

### New Dataset

Let's go through an example of contributing a new dataset called `my_new_dataset` which contains a new 1D C&P dataset.
1. Edit the `1d/README.md` file to include a new entry for `my_new_dataset` in alphabetical order, following the format of existing entries. For example:
    - [`my_new_dataset`](my_new_dataset)
        - Author(s). (Year). Title of the publication. Journal/Conference, Volume(Issue), Page numbers. DOI: https://doi.org/xxxx
        - A very brief description of the dataset and its characteristics.
1. Create a new folder `1d/my_new_dataset` and add your source files there.
1. Make sure the `1d/my_new_dataset` directory contains a `README.md` file describing the contents, characteristics and the file format in detail.
1. Commit your changes and submit a pull request for review.

Ensure to always provide proper reference with DOI for the dataset (can be either a preprint or published version).
We also welcome converted datasets, but do require the original source files to also exist in the repository.

> [!TIP]
> See [this pull request](https://github.com/ESICUP/datasets/pull/3) as an example of a new dataset contribution to this repository.

### Corrections and Improvements

This repository started off as a direct clone of the ESICUP datasets webpage.
However, some entries contained incomplete/messy descriptions and/or files.

If you detect any errors, inconsistencies or have suggestions for improvements, please feel free to [submit an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) or (preferably) [open a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) with the necessary changes.
