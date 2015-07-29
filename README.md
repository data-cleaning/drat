# drat
Beta versions of data-cleaning packages

To install a package from our ```drat``` repository, first install Dirk Eddelbuetel's ```drat``` package from ```CRAN```.

```
install.packages("drat")
```

After that you can install packages from our ```drat``` repo as follows (for example, for the `validate` package).
```
drat::addRepo("data-cleaning")
install.packages("validate")
```




