[![Chameleon](https://github.com/chris1111/Chameleon/actions/workflows/Build.yml/badge.svg)](https://github.com/chris1111/Chameleon/actions/workflows/Build.yml)
# Chameleon
- Chameleon base branch Enoch


Chameleon is a Darwin/XNU boot loader based on Apple's boot-132.

Because Chameleon now uses part of GPL V2 licensed code in 2 files,
it *must* conform to the most restrictive license that it uses that is the:
GPL Version 2 LICENSE

Chameleon can thus be (and has to be) freely distributed under the term of the GPL V2 license which prevails, as it is the most restrictive license.

### It must be compiled in macOS High Sierra. Xcode Version 9.4.1 (9F2000)

### Usage: ⬇︎
- Git Clone

``` bash
git clone https://github.com/chris1111/Chameleon.git
```

### Build: ⬇︎

``` bash
cd ./Chameleon 
make clean
```

``` bash
cd ./Chameleon 
make
```

### Look in `sym` folder, everythings is building there.
- `make pkg` If you want to build Package.
