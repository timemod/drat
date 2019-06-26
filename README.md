# drat

Install `timemod` (Timeseries and Models) packages 

To install a package from our ```drat``` repository, first install Dirk Eddelbuetel's ```drat``` package from ```CRAN```.

```
install.packages("drat")
```

After that you can install packages from our ```drat``` repo as follows 
(for example, for the `regts` package).
```
drat::addRepo("timemod")
install.packages("regts")
```

And for the `dynmdl`:
drat::addRepo("timemod")
install.packages("dynmdl")
```

The last command also installs `regts` because `dyndml` depends on `regts`.
