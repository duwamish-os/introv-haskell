
created using [`cabal init`](https://www.haskell.org/cabal/users-guide/developing-packages.html)

```
$ ghc --version
The Glorious Glasgow Haskell Compilation System, version 8.2.1
```

```
# use cabal help to understand cabal commands

$ cabal install
Warning: --root-cmd is no longer supported, see
https://github.com/haskell/cabal/issues/3353 (if you didn't type --root-cmd,
comment out root-cmd in your ~/.cabal/config file)
Warning: The package list for 'hackage.haskell.org' is 21 days old.
Run 'cabal update' to get the latest list of available packages.
Resolving dependencies...
Configuring introv-haskell-0.1.0.0...
Building introv-haskell-0.1.0.0...
Installed introv-haskell-0.1.0.0
Updating documentation index
/Users/prayagupd/Library/Haskell/share/doc/x86_64-osx-ghc-8.2.1/index.html

$ cabal run
Preprocessing executable 'introv-haskell' for introv-haskell-0.1.0.0..
Building executable 'introv-haskell' for introv-haskell-0.1.0.0..
Running introv-haskell...
Hello, Haskell!
```
