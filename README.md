About datasets
==============

Home: https://github.com/huggingface/datasets

Package license: Apache-2.0

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/datasets-feedstock/blob/master/LICENSE.txt)

Summary: HuggingFace/Datasets is an open library of NLP datasets.

Development: https://github.com/huggingface/datasets

Documentation: https://huggingface.co/docs/datasets/

Datasets is a lightweight library providing one-line dataloaders for many
public datasets and one liners to download and pre-process any of the number
of datasets major public datasets provided on the HuggingFace Datasets Hub.
Datasets are ready to use in a dataloader for training/evaluating a ML model
(Numpy/Pandas/PyTorch/TensorFlow/JAX). Datasets also provide an API for
simple, fast, and reproducible data pre-processing for the above public
datasets as well as your own local datasets in CSV/JSON/text.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=11361&branchName=master">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/datasets-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-datasets-green.svg)](https://anaconda.org/conda-forge/datasets) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/datasets.svg)](https://anaconda.org/conda-forge/datasets) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/datasets.svg)](https://anaconda.org/conda-forge/datasets) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/datasets.svg)](https://anaconda.org/conda-forge/datasets) |

Installing datasets
===================

Installing `datasets` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `datasets` can be installed with:

```
conda install datasets
```

It is possible to list all of the versions of `datasets` available on your platform with:

```
conda search datasets --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating datasets-feedstock
===========================

If you would like to improve the datasets recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/datasets-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Tata17](https://github.com/Tata17/)
* [@mxr-conda](https://github.com/mxr-conda/)
* [@oblute](https://github.com/oblute/)
* [@thewchan](https://github.com/thewchan/)
* [@wietsedv](https://github.com/wietsedv/)

