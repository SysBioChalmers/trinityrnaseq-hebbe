[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/3239)

This repository hosts just the Singularity recipe that is used to automatically build the latest image up on Singularity Hub. A custom recipe was needed for the image to run on the Hebbe cluster.

[The original source code is here](https://github.com/trinityrnaseq/trinityrnaseq)

To obtain the `Singularity` file, the `Dockerfile` from the `2.8.5` release was copied here and converted to a `Singularity.spython` recipe with `spython` into after which it was manually tweaked.
