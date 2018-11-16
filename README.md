# dwc2parquet
converts darwin core archive to apache parquet

## install

1. install singularity v3.0 https://www.sylabs.io/guides/3.0/user-guide/


## build

1. run ```sudo singularity build dwc2parquet.sif dwc2parquet.def```

## install

1. sudo cp [build dir]/dwc2parquet.sif /usr/local/bin/dwc2parquet

## usage 

dwc2parquet [dwc meta.xml url] ...

## example

```console
$ wget -O dwca.zip https://deeplinker.bio/5cba2f513fee9e1811fe023d54e074df2d562b4169b801f15abacd772e7528f8 
$ unzip dwca.zip
$ dwc2parquet.sif meta.xml

