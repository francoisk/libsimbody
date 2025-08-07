# libsimbody - A C++ library

This is a `build2` package for the [`<UPSTREAM-NAME>`](https://<UPSTREAM-URL>)
C++ library. It provides <SUMMARY-OF-FUNCTIONALITY>.

@@ TODO Note that the Visualizer application is not supported.

## Usage

To start using `libsimbody` in your project, add the following `depends`
value to your `manifest`, adjusting the version constraint as appropriate:

```
depends: libsimbody ^<VERSION>
```

Then import the library in your `buildfile`:

```
import libs = libsimbody%lib{<TARGET>}
```


## Importable targets

This package provides the following importable targets:

```
lib{<TARGET>}
```

<DESCRIPTION-OF-IMPORTABLE-TARGETS>


## Configuration variables

This package provides the following configuration variables:

```
[bool] config.libsimbody.<VARIABLE> ?= false
```

<DESCRIPTION-OF-CONFIG-VARIABLES>
