# attempt_blobtoolkit

Attempt to run blobtoolkit on a small public dataset, on MacOS v10.13.6. This pipeline kinda reminds me of nextstrain...altho for different purposes.

## Citations

* Challis, R., Richards, E., Rajan, J., Cochrane, G. and Blaxter, M., 2020. [BlobToolKit–Interactive quality assessment of genome assemblies](https://pubmed.ncbi.nlm.nih.gov/32071071/). G3: Genes, Genomes, Genetics, 10(4), pp.1361-1374.
* Laetsch, D.R. and Blaxter, M.L., 2017. [BlobTools: Interrogation of genome assemblies](https://f1000research.com/articles/6-1287). F1000Research, 6(1287), p.1287.
* [Main Blobtoolkit Genomie Hubs Website](https://blobtoolkit.genomehubs.org/)

## Dependendencies

According to [BlobToolKit documentation](https://blobtoolkit.genomehubs.org/install/), seems to require:

* [Install Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
* [Install Firefox](https://www.mozilla.org/en-US/firefox/new/)
* [Install X11](https://kb.thayer.dartmouth.edu/article/336-x11-for-windows-and-mac)


```
git clone https://github.com/blobtoolkit/blobtools2.git
```

When in python, use `venv` or `conda`. I'm on MacOS v10.13.6 with brew-installed venv

```
python3 -m venv blobworld
# conda create -n btk_env

source blobworld/bin/activate
pip install -r blobtoolkit/requirements.txt
```

