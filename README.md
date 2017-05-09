# STAR.env

For local development, I used the star bioconda package

1) if necessary, install conda
    https://conda.io/miniconda.html

    I used Python 2.7 64-bit (bash installer) for Mac OS X

2) create an environment

    # first I created an empty python/2.7 environment
    conda create --name star-env python=2.7

    # then I installed star/2.5.2b into the environment
    conda install -c bioconda --name star-env star=2.5.2b 

3) activate the environment
    source activate star-env

    note: to deactivate
    source deactivate star-env
