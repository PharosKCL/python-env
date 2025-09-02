# WP2 - Python package requirements 

This repo documents Python (and other) packages requested as part of the Pharos WP2 [tech stack V1](https://emckclac.sharepoint.com/:x:/r/sites/MT-RMI-PAI/Shared%20Documents/Tech/Work_packages/WP2_ML_user_stories/Pharos_Tech_Stack_V1.xlsx?d=wafdd41c98a654218808e5afb852fdccf&csf=1&web=1&e=bSieSU).
The package versions in `pixi.toml` are compatible with each other for installation in the same virtual environment.
Practical usage of these packages has not yet been tested, however.

## Usage

To install these packages, first [install `pixi`](https://pixi.sh/latest/installation/)

Then ensure you are in this repo directory and install the packages:

```
pixi install
```

The Pixi manifest file (`pixi.toml`) defines which platforms are supported. 
In theory this project is supported on both `linux-64` and `osx-arm64`, but installation on Linux has not yet been tested.
