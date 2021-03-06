# exchangedataset-python

`exchangedataset-python` is a library for Python 3 to allow easy integration of the Exchangedataset service.

## About Exchangedataset

[Exchangedataset](https://www.exchangedataset.cc/) is the historical cryptocurrency market data streaming service.

## Requirements

- Python 3.8 or more
- Pipenv

## License

MIT License

This library is free to distribute and modify under the condition that you include a license notice.

## Install Library

You can install the package by `pip3` command:

```shell
pip3 install exchangedataset-python
```

This will install the latest and available version of this library.

As shown above, its package name in PyPi is [`exchangedataset-python`](https://pypi.org/project/exchangedataset-python/).

## Import

The module is named `exdpy`.
Please note that it is different from the package name.

```python
import exdpy
```

## Development

This information is for the developer of this library.

Thank you for your contribution.

### Environment Setup

This project utilizes [Pipenv](https://pypi.org/project/pipenv/).

It is a package managing and virtual environment utility.

To fetch all dependencies (including development dependencies), run the command below:

```shell
pipenv install --dev
```

This will install all dependencies needed to run `exchangedataset-python`.

### Test

Unit test files are under tests/ directory.

All tests can be conducted by running the command below:

```shell
pipenv run pytest
```

### Documentation Generation

API Documentation can be generated by running the below command in `sphinx` directory:

```shell
pipenv run make
```

### Deploy

The command below will package all python files under the exdpy directory and upload it to PyPi.

```shell
pipenv run setup.py upload
```
