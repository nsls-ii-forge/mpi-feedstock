About mpi
=========

Home: https://github.com/conda-forge/mpi-feedstock

Package license: BSD 3-clause

Feedstock license: BSD 3-Clause

Summary: Metapackage to select the MPI variant. Use conda's pinning mechanism in your environment to control which variant you want.



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=51&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/mpi-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_mpimpich</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=51&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/mpi-feedstock?branchName=master&jobName=linux&configuration=linux_mpimpich" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_mpiopenmpi</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=51&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/mpi-feedstock?branchName=master&jobName=linux&configuration=linux_mpiopenmpi" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_mpimpich</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=51&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/mpi-feedstock?branchName=master&jobName=osx&configuration=osx_mpimpich" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_mpiopenmpi</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=51&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/mpi-feedstock?branchName=master&jobName=osx&configuration=osx_mpiopenmpi" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>
      <img src="https://img.shields.io/badge/Windows-disabled-lightgrey.svg" alt="Windows disabled">
    </td>
  </tr>
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mpi-green.svg)](https://anaconda.org/nsls2forge/mpi) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/mpi.svg)](https://anaconda.org/nsls2forge/mpi) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/mpi.svg)](https://anaconda.org/nsls2forge/mpi) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/mpi.svg)](https://anaconda.org/nsls2forge/mpi) |

Installing mpi
==============

Installing `mpi` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `mpi` can be installed with:

```
conda install mpi
```

It is possible to list all of the versions of `mpi` available on your platform with:

```
conda search mpi --channel nsls2forge
```




Updating mpi-feedstock
======================

If you would like to improve the mpi recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/mpi-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@minrk](https://github.com/minrk/)
* [@ocefpaf](https://github.com/ocefpaf/)

