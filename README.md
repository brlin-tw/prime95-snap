# Unofficial snap packaging for Prime95

This project provides an unofficial snap package for Prime95, a popular software for stress testing and benchmarking CPUs.

<https://gitlab.com/brlin/prime95-snap>  
[![The GitLab CI pipeline status badge of the project's `main` branch](https://gitlab.com/brlin/prime95-snap/badges/main/pipeline.svg?ignore_skipped=true "Click here to check out the comprehensive status of the GitLab CI pipelines")](https://gitlab.com/brlin/prime95-snap/-/pipelines) [![GitHub Actions workflow status badge](https://github.com/brlin-tw/prime95-snap/actions/workflows/check-potential-problems.yml/badge.svg "GitHub Actions workflow status")](https://github.com/brlin-tw/prime95-snap/actions/workflows/check-potential-problems.yml) [![pre-commit enabled badge](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "This project uses pre-commit to check potential problems")](https://pre-commit.com/) [![REUSE Specification compliance badge](https://api.reuse.software/badge/gitlab.com/brlin/prime95-snap "This project complies to the REUSE specification to decrease software licensing costs")](https://api.reuse.software/info/gitlab.com/brlin/prime95-snap)

\#prime95 \#snap-packaging

## References

The following resources are referenced during the development of this project:

* [GIMPS - Free Prime95 software downloads - PrimeNet](https://www.mersenne.org/download/)  
  Available downloads and verification hashes of the Prime95 software.
* [Software End User License Agreement ("EULA") - GIMPS Legalese - PrimeNet](https://www.mersenne.org/legal/#EULA)  
  Explains what's allowed and what's not allowed regarding the use of the Prime95 software.
* [snapcrafters/sommelier-core: Package a Windows application for Linux using a Snap with Wine.](https://github.com/snapcrafters/sommelier-core)  
  Explains how to implement a Wine snap package.
* [\[Enhancement\]: list of wine-platform snaps available? · Issue #36 · snapcrafters/sommelier-core](https://github.com/snapcrafters/sommelier-core/issues/36)  
  Explains how to search for the available Wine platform snaps.
* [xnote-stopwatch-snap/snap/local/launchers/xnote-stopwatch-launch at 599155d · brlin-tw/xnote-stopwatch-snap](https://github.com/brlin-tw/xnote-stopwatch-snap/blob/599155d/snap/local/launchers/xnote-stopwatch-launch)  
  Reference implementation of the snap launcher script for a Wine snap package.

## Licensing

Unless otherwise noted([comment headers](https://reuse.software/spec-3.3/#comment-headers)/[REUSE.toml](https://reuse.software/spec-3.3/#reusetoml)), this product is licensed under [the 4.0 International version of the Creative Commons Attribution-ShareAlike License](https://creativecommons.org/licenses/by-sa/4.0/), or any of its more recent versions of your preference.

This work complies to [the REUSE Specification](https://reuse.software/spec/), refer to the [REUSE - Make licensing easy for everyone](https://reuse.software/) website for info regarding the licensing of this product.
