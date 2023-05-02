## Running this

Take a look at main.sw's test_read_write() -- it really should fail,
but is successful.

```
forc test
```

## My versions

```
$ fuelup show
Default host: aarch64-apple-darwin
fuelup home: /Users/trevor/.fuelup

installed toolchains
--------------------
latest-aarch64-apple-darwin (default)
0.37.1
hyperlane

active toolchain
-----------------
latest-aarch64-apple-darwin (default)
  forc : 0.38.0
    - forc-client
      - forc-deploy : 0.38.0
      - forc-run : 0.38.0
    - forc-doc : 0.38.0
    - forc-explore : 0.28.1
    - forc-fmt : 0.38.0
    - forc-index : 0.10.0
    - forc-lsp : 0.38.0
    - forc-wallet : 0.2.2
  fuel-core : 0.17.11
  fuel-indexer : 0.10.0
```