

### Magma

A [Magma](https://magmafoundation.org/) server, which is a combination of Forge and PaperMC, can be used with

    -e TYPE=MAGMA

!!! note

The Magma project [has benn terminated](https://git.magmafoundation.org/magmafoundation/magma-1-20-x/-/commit/4e7abe37403c47d09b74b77bcfc26a19b18f5891). Please use Ketting for 1.20.2+.

There are limited base versions supported, so you will also need to  set `VERSION`, such as "1.12.2", "1.16.5", etc.


### Ketting

A [Ketting](https://github.com/kettingpowered/Ketting-1-20-x) server, which is a alternative project of Magma 1.20+, can be used with

    -e TYPE=KETTING

There are limited base versions supported, so you will also need to  set `VERSION`, such as "1.20.2" or later.

In addition, `FORGE_VERSION` and `KETTING_VERSION` must be specified. You can find the supported `FORGE_VERSION` in the [project page](https://github.com/kettingpowered/Ketting-1-20-x), and `KETTING_VERSION` in the [release page](https://github.com/kettingpowered/Ketting-1-20-x/releases).

!!! note

The length of `KETTING_VERSION` is 8, not 7 since it is taken from an abbreviated git commit hash. The value can be found in a jar file link on an Assets section for each releases.


### Mohist

A [Mohist](https://github.com/MohistMC/Mohist) server can be used with

    -e TYPE=MOHIST

!!! note

There are limited base versions supported, so you will also need to  set `VERSION`, such as "1.12.2"

By default the latest build will be used; however, a specific build number can be selected by setting `MOHIST_BUILD`, such as

    -e VERSION=1.16.5 -e MOHIST_BUILD=374

### Catserver

A [Catserver](http://catserver.moe/) type server can be used with

    -e TYPE=CATSERVER

> **NOTE** Catserver only provides a single release stream, so `VERSION` is ignored
