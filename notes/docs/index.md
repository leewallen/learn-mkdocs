# Welcome to my MkDocs Notes

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Setup

I created a virtual environment called `mkdocs`.

```shell
❯ python3 -m venv mkdocs
❯ source mkdocs/bin/activate
```

### Install MkDocs

Then I installed MkDocs:

```shell
❯ pip install mkdocs
Collecting mkdocs
  Downloading mkdocs-1.2.3-py3-none-any.whl (6.4 MB)
     |████████████████████████████████| 6.4 MB 4.5 MB/s
Collecting watchdog>=2.0
  Downloading watchdog-2.1.6-cp38-cp38-macosx_10_9_x86_64.whl (85 kB)
     |████████████████████████████████| 85 kB 18.3 MB/s
Collecting pyyaml-env-tag>=0.1
  Downloading pyyaml_env_tag-0.1-py3-none-any.whl (3.9 kB)
Collecting click>=3.3
  Downloading click-8.0.3-py3-none-any.whl (97 kB)
     |████████████████████████████████| 97 kB 22.4 MB/s
Collecting Jinja2>=2.10.1
  Downloading Jinja2-3.0.3-py3-none-any.whl (133 kB)
     |████████████████████████████████| 133 kB 56.0 MB/s
Collecting mergedeep>=1.3.4
  Downloading mergedeep-1.3.4-py3-none-any.whl (6.4 kB)
Collecting ghp-import>=1.0
  Downloading ghp_import-2.0.2-py3-none-any.whl (11 kB)
Collecting packaging>=20.5
  Downloading packaging-21.3-py3-none-any.whl (40 kB)
     |████████████████████████████████| 40 kB 25.1 MB/s
Collecting Markdown>=3.2.1
  Downloading Markdown-3.3.6-py3-none-any.whl (97 kB)
     |████████████████████████████████| 97 kB 25.9 MB/s
Collecting importlib-metadata>=3.10
  Downloading importlib_metadata-4.11.0-py3-none-any.whl (17 kB)
Collecting PyYAML>=3.10
  Downloading PyYAML-6.0-cp38-cp38-macosx_10_9_x86_64.whl (192 kB)
     |████████████████████████████████| 192 kB 53.5 MB/s
Collecting MarkupSafe>=2.0
  Downloading MarkupSafe-2.0.1-cp38-cp38-macosx_10_9_x86_64.whl (13 kB)
Collecting python-dateutil>=2.8.1
  Using cached python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
Collecting pyparsing!=3.0.5,>=2.0.2
  Downloading pyparsing-3.0.7-py3-none-any.whl (98 kB)
     |████████████████████████████████| 98 kB 25.3 MB/s
Collecting zipp>=0.5
  Downloading zipp-3.7.0-py3-none-any.whl (5.3 kB)
Collecting six>=1.5
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Installing collected packages: watchdog, PyYAML, pyyaml-env-tag, click, MarkupSafe, Jinja2, mergedeep, six, python-dateutil, ghp-import, pyparsing, packaging, zipp, importlib-metadata, Markdown, mkdocs
Successfully installed Jinja2-3.0.3 Markdown-3.3.6 MarkupSafe-2.0.1 PyYAML-6.0 click-8.0.3 ghp-import-2.0.2 importlib-metadata-4.11.0 mergedeep-1.3.4 mkdocs-1.2.3 packaging-21.3 pyparsing-3.0.7 python-dateutil-2.8.2 pyyaml-env-tag-0.1 six-1.16.0 watchdog-2.1.6 zipp-3.7.0
```

## First MkDocs

MkDocs is very easy to start using. Just create a MkDocs project and modify the generated files.

### Create MkDocs Project

I created an example project named `example_01`:

```shell
❯ mkdocs new example_01
INFO     -  Creating project directory: example_01
INFO     -  Writing config file: example_01/mkdocs.yml
INFO     -  Writing initial docs: example_01/docs/index.md
```


## Theme

Tried out the `gitbook` theme. The theme's repo can be found [here](https://gitlab.com/lramage/mkdocs-gitbook-theme).

