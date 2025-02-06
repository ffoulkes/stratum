# ffoulkes/stratum

> See [README.stratum.md](README.stratum.md) for the original README file.

## Background

In January 2025, Intel decided to roll the IPDK networking-recipe `main`
branch (and its submodules) back to their `mev-ts-1.9` release
(Sep 30, 2024), effectively discarding the work I had done since then.
This fork allows me to keep tinkering without stepping on their toes.

## Contents

This repository is a fork of <https://github.com/stratum/stratum>. It is a
submodule of <https://github.com/ffoulkes/networking-recipe>.

The `ffoulkes` branch was imported from <https://github.com/ipdk-io/stratum-dev>.
It contains the changes made for IPDK.

Its baseline is
[IPDK Stratum v3.3.0.0](https://github.com/ipdk-io/stratum-dev/releases/tag/v3.3.0.0).

## Tags

- `idpk-base` marks the point at which IPDK development diverged from the
  Stratum `main` branch.
  
  Subsequent changes to Stratum `main` were cherry-picked into the IPDK branch
  in 2023 and 2024, and are part of the `ffoulkes` branch.

- `mev-ts-1.9` marks the point at which the `ffoulkes` branch diverged from
  the IPDK `main` branch.
