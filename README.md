

# deephaven-core-test-data

This repository contains open source data sets. They are intended to be used as part of testing to the Deephaven Community Core Engine. For more information, check out [Deephaven Community Core](https://github.com/deephaven/deephaven-core).

## Table of Contents

The following folders can be found in this repository:

- **parquetFiles** - Files in various parquet formats to test functionality of importing parquet files.


## Description

Each folder in this repository has the following structure within:

 - `README` - An explanation of everything about the data
 - `data` - A folder with all relevant data in needed format


## Installation Instructions

1. Follow the README instructions on [Deephaven Community Core](https://github.com/deephaven/deephaven-core) for installing the code studio and all required dependencies.

2. The repository uses [GitHub large file support](https://git-lfs.github.com/).  Follow the directions in the link to install.  If you are using Mac, you need to:

```
brew install git-lfs
git lfs install
```

3. Execute the command to clone the test repository:

```
gh repo clone deephaven/deephaven-core-test-data
```

4. Move these Parquet to your deephaven-core clone, for example, if they are on the same room directory from that directory execute the command:
```
cp -R deephaven-core-test-data/parquetFiles deephaven-core/docker/core/data
```

## License

Provided under the [Apache 2.0 license](./LICENSE)
