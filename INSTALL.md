# Installation

## Using `uv`

```bash
uv venv  # create a virtual environment
source .venv/bin/activate

uv sync --extra build  # install dependencies in the `build` group
uv sync --extra build --extra compile  # compile extra libraries without removing the `build` group 
```

Then you may follow the instructions in the [README](README.md) to run the project.

The setup has been tested on Arch Linux as of mid-May 2025, using Python 3.13.3, CUDA 12.8 and PyTorch 2.7.0.
