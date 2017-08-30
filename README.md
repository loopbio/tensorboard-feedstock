About tensorboard
=================

Home: https://github.com/tensorflow/tensorboard

Package license: Apache 2.0

Feedstock license: BSD 3-Clause

Summary: TensorFlow's Visualization Toolkit



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/loopbio/tensorboard-feedstock.svg?style=shield)](https://circleci.com/gh/loopbio/tensorboard-feedstock)
OSX: [![TravisCI](https://travis-ci.org/loopbio/tensorboard-feedstock.svg?branch=master)](https://travis-ci.org/loopbio/tensorboard-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/loopbio/tensorboard-feedstock?svg=True)](https://ci.appveyor.com/project/loopbio/tensorboard-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/loopbio/tensorboard/badges/version.svg)](https://anaconda.org/loopbio/tensorboard)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/loopbio/tensorboard/badges/downloads.svg)](https://anaconda.org/loopbio/tensorboard)

Installing tensorboard
======================

Installing `tensorboard` from the `loopbio` channel can be achieved by adding `loopbio` to your channels with:

```
conda config --add channels loopbio
```

Once the `loopbio` channel has been enabled, `tensorboard` can be installed with:

```
conda install tensorboard
```

It is possible to list all of the versions of `tensorboard` available on your platform with:

```
conda search tensorboard --channel loopbio
```




Updating tensorboard-feedstock
==============================

If you would like to improve the tensorboard recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`loopbio` channel, whereupon the built conda packages will be available for
everybody to install and use from the `loopbio` channel.
Note that all branches in the loopbio/tensorboard-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
