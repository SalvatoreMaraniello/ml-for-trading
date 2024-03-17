

## Get started

```sh
python3 -m venv venv
source venv/bin/activate
pip3 install --upgrade pip
pip3 install -r requirements.txt
```


## Notebooks

You find them in the [notebooks](notebooks) directory. 

- [get-stock-data.ipynb](notebooks/get-stock-data.ipynb). Download stock data and basic manipulations.

- 




## Git submodules

This folder tracks a number of remote repos as submodules. See `.gitmodules` file for details. 

To add new submodules under `./submodules`:
```sh
git submodule add https://github.com/xxx ./submodules/xxx
```


