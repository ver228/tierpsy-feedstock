About tierpsy
=============

Home: https://github.com/ver228/tierpsy-tracker

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: Tierpsy Tracker Multi-Worm Tracker



Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/ver228/tierpsy-feedstock/master.svg?label=Linux)](https://circleci.com/gh/ver228/tierpsy-feedstock)
[![OSX](https://img.shields.io/travis/ver228/tierpsy-feedstock/master.svg?label=macOS)](https://travis-ci.org/ver228/tierpsy-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/ver228/tierpsy-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/ver228/tierpsy-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-tierpsy-green.svg)](https://anaconda.org/ver228/tierpsy) | [![Conda Downloads](https://img.shields.io/conda/dn/ver228/tierpsy.svg)](https://anaconda.org/ver228/tierpsy) | [![Conda Version](https://img.shields.io/conda/vn/ver228/tierpsy.svg)](https://anaconda.org/ver228/tierpsy) | [![Conda Platforms](https://img.shields.io/conda/pn/ver228/tierpsy.svg)](https://anaconda.org/ver228/tierpsy) |

Installing tierpsy
==================

Installing `tierpsy` from the `ver228` channel can be achieved by adding `ver228` to your channels with:

```
conda config --add channels ver228
```

Once the `ver228` channel has been enabled, `tierpsy` can be installed with:

```
conda install tierpsy
```

It is possible to list all of the versions of `tierpsy` available on your platform with:

```
conda search tierpsy --channel ver228
```




Updating tierpsy-feedstock
==========================

If you would like to improve the tierpsy recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ver228` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ver228` channel.
Note that all branches in the conda-forge/tierpsy-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
