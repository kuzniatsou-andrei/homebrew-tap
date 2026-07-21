# homebrew-tap

Homebrew tap for [Pathfinder](https://github.com/kuzniatsou-andrei/pathfinder).

## Install

    brew tap kuzniatsou-andrei/tap
    brew trust kuzniatsou-andrei/tap
    brew install --cask pathfinder

The `brew trust` step is required on Homebrew >= 4.7 for third-party
(non-homebrew-core) casks; without it `brew install --cask` refuses with
*"Refusing to load cask ... from untrusted tap"*.
