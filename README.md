# SudachiDict

A lexicon for Japanese tokenizer
[Sudachi](https://github.com/WorksApplications/Sudachi/).

## Latest version

* [sudachi-dictionary-20200722-small.zip](https://object-storage.tyo2.conoha.io/v1/nc_2520839e1f9641b08211a5c85243124a/sudachi/sudachi-dictionary-20200722-small.zip) ([sudachi-dictionary-latest-small.zip](https://object-storage.tyo2.conoha.io/v1/nc_2520839e1f9641b08211a5c85243124a/sudachi/sudachi-dictionary-latest-small.zip))
* [sudachi-dictionary-20200722-core.zip](https://object-storage.tyo2.conoha.io/v1/nc_2520839e1f9641b08211a5c85243124a/sudachi/sudachi-dictionary-20200722-core.zip) ([sudachi-dictionary-latest-core.zip](https://object-storage.tyo2.conoha.io/v1/nc_2520839e1f9641b08211a5c85243124a/sudachi/sudachi-dictionary-latest-core.zip))
* [sudachi-dictionary-20200722-full.zip](https://object-storage.tyo2.conoha.io/v1/nc_2520839e1f9641b08211a5c85243124a/sudachi/sudachi-dictionary-20200722-full.zip) ([sudachi-dictionary-latest-full.zip](https://object-storage.tyo2.conoha.io/v1/nc_2520839e1f9641b08211a5c85243124a/sudachi/sudachi-dictionary-latest-full.zip))

### Python packages

You can install the dictionaries for [WorksApplications/SudachiPy](https://github.com/WorksApplications/SudachiPy), the Python version of Sudachi, as Python packages.

```bash
$ pip install sudachidict_core
```

```bash
$ pip install sudachidict_small
$ sudachipy link -t small
```

```bash
$ pip install sudachidict_full
$ sudachipy link -t full
```

* [SudachiDict-small · PyPI](https://pypi.org/project/SudachiDict-small/)
* [SudachiDict-core · PyPI](https://pypi.org/project/SudachiDict-core/)
* [SudachiDict-full · PyPI](https://pypi.org/project/SudachiDict-full/)


## Dictionary types

Sudachi has three types of dictionaries.

* Small: includes only the vocabulary of UniDic
* Core: includes basic vocabulary (default)
* Full: includes miscellaneous proper nouns

## Build from sources

SudachiDict needs [Git LFS](https://git-lfs.github.com/) to download the sourses
of the system dictionaries. If you fail to build the dictionaries, install
Git LFS and `git lfs pull`.

Building the dictionaries fails with a locale other than UTF-8.
Add `-Dfile.encoding=UTF-8` to `MAVEN_OPTS`.


## Licenses

SudachiDict by Works Applications Co., Ltd. is licensed under the [Apache License, Version2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

   Copyright (c) 2017 Works Applications Co., Ltd.
  
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at
  
       http://www.apache.org/licenses/LICENSE-2.0
  
   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   
This project includes UniDic and a part of NEologd.

- http://unidic.ninjal.ac.jp/
- https://github.com/neologd/mecab-ipadic-neologd
