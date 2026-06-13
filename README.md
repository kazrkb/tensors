# tensors

A small collection of PyTorch tensor experiments and examples, captured in a single Jupyter notebook.

## Contents

- `tensors.ipynb` — interactive Jupyter notebook demonstrating tensor creation, manipulation, and basic operations using PyTorch.
- `LICENSE` — repository license.

## Requirements

- Python 3.8 or newer
- PyTorch (see installation commands below)
- Jupyter Notebook or JupyterLab (recommended)

## Quick start

1. Clone the repo:

```
git clone https://github.com/kazrkb/tensors.git
cd tensors
```

2. (Optional) Create and activate a virtual environment:

Windows:

```
python -m venv venv
venv\Scripts\activate
```

macOS / Linux:

```
python3 -m venv venv
source venv/bin/activate
```

3. Install PyTorch and Jupyter (choose the correct PyTorch command from https://pytorch.org if you need CUDA support):

```
pip install --upgrade pip
pip install torch jupyterlab
```

4. Open the notebook:

```
jupyter notebook tensors.ipynb
```

Or open `tensors.ipynb` directly in VS Code.

## What you'll find in the notebook

- Examples of creating tensors with different shapes and dtypes
- Basic arithmetic, indexing, and slicing
- In-place vs. out-of-place operations
- Device placement examples (CPU vs GPU) where applicable

## Notes on GPU / CUDA

If you have a CUDA-enabled GPU, install a matching PyTorch build (see https://pytorch.org/get-started/locally/). The notebook contains examples that will detect and use CUDA when available.

## Contributing

This repository is minimal. Feel free to open issues or submit pull requests with improvements, additional examples, or fixes.

## License

See the `LICENSE` file for license terms.

---

Repository owner: kazrkb
