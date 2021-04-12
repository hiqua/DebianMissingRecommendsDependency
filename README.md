# DebianMissingRecommendsDependency

To build:
```sh
equivs-build pack.equivs
```


Then install using:
```sh
apt-get install ./pack_99_all.deb
```


Change the Recommends / Depends dependencies in `pack.equivs`.

Results:
* does not install with an unknown package in Depends
* installs with an unknown package in Recommends
