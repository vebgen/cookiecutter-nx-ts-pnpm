# cookiecutter template for a monorepo with Nx

This is a [cookiecutter](https://github.com/cookiecutter/cookiecutter)
template for a typescript monorepo with [Nx](https://nx.dev/)
and [pnpm](https://pnpm.io/next/).

## Pre-requisites

To install cookiecutter, make sure you have a modern version of Python (>= 3.7)
available, then run:

```bash
python -m pip install --user cookiecutter
```

## Usage

Then, either clone this project locally, make some changes, then run:

```bash
git clone https://github.com/vebgen/cookiecutter-nx-ts-pnpm.git
# changes ...
python -m cookiecutter cookiecutter-nx-ts-pnpm
```

Or, if you want to use this template directly from GitHub, run:

```bash
python -m cookiecutter  gh:vebgen/cookiecutter-nx-ts-pnpm
```

## After running cookiecutter

After running cookiecutter, you will have a new folder with the name you
specified in the `project_slug` variable. This folder will contain a
[pnpm](https://pnpm.io/next/) based 
[monorepo](https://en.wikipedia.org/wiki/Monorepo). Start by installing
the dependencies:

```bash
cd cookiecutter_project_slug
pnpm install
```
