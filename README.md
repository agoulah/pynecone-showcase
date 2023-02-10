# What is it?

This is just a simple project showcasing all the pynecone components.

The full page fit in a single file, you can either:
- clone the project then follow "How to use"
- copy the file `pynecone_showcase.py`


It's purpose is to be used by contributors to [Pynecone](https://github.com/pynecone-io/pynecone.git) so they can easily check if any of their PR has detrimental impact on some components.

As much as possible, this repo will try to avoid using workaround, so as not to hide any potential problem.

# How to use?

## Standalone

### With virtualenvwrapper

1. `git clone git@github.com:Lendemor/pynecone-showcase.git`
1. `mkvirtualenv pynecone-showcase`
2. `pip install git+https://github.com/pynecone-io/pynecone.git@main`
4. `pc init`
5. `pc run`

> For more complete steps on running Pynecone, visit the official repo !

### With something else

Send me the steps on how you'd set it up, and I'll gladly add it

## Inside pynecone main project
### Unix system
Steps:
- `cd /your/workspace/`
- `git clone git+https://github.com/pynecone-io/pynecone.git`
- `git clone git@github.com:Lendemor/pynecone-showcase.git`
- `cd pynecone; mkdir -p "examples/test"; poetry run pc init`
- `ln -sf pynecone-showcase/pynecone-showcase/pynecone-showcase.py pynecone/examples/test/test/test.py`

## Preview

![A preview of Pynecone Showcase](https://github.com/Lendemor/pynecone-showcase/raw/master/preview.png)
