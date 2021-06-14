[安装R](https://docs.rstudio.com/resources/install-r/#optional-install-recommended-packages)

R包

```R 
# R console
install.packages(c("pcalg","kpcalg","bnlearn","sparsebn","SID","CAM","D2C","RCIT"))
```

```sh
# bash console
Rscript -e 'install.packages("BiocManager")'
Rscript -e 'BiocManager::install(c("CAM", "SID", "bnlearn", "pcalg", "kpcalg", "D2C"))'
```
