# SOP4CWD Website

This repository contains the source content and configuration for the [SOP4CWD](https://sop4cwd.org/) website. The site is built with [MkDocs](https://www.mkdocs.org/) using the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.

The Surveillance Optimization Project for Chronic Wasting Disease (SOP4CWD) is a collaboration among [Cornell Wildlife Health Lab](https://cwhl.vet.cornell.edu/) and wildlife agencies working to help agencies across North America respond to chronic wasting disease (CWD). Learn more at [sop4cwd.org](https://sop4cwd.org/).

## Repository structure

- `docs/` — Markdown content, images, and stylesheets that make up the site
- `overrides/` — Theme template overrides for Material for MkDocs
- `mkdocs.yml` — Site configuration and navigation
- `pyproject.toml` / `uv.lock` — Python dependencies managed by [uv](https://docs.astral.sh/uv/)
- `requirements.txt` — Legacy dependency list (kept for compatibility)

## Running the website locally

This project uses [uv](https://docs.astral.sh/uv/) to manage Python and its dependencies.

### 1. Install uv

See the [uv installation instructions](https://docs.astral.sh/uv/getting-started/installation/). 

On macOS / Linux:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

On Windows (PowerShell):

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### 2. Install dependencies

From the repository root:

```bash
uv sync
```

This creates a virtual environment in `.venv/` and installs the pinned dependencies from `uv.lock`.

### 3. Start the local dev server

```bash
uv run mkdocs serve
```

Then open <http://127.0.0.1:8000> in your browser. The site auto-reloads when you edit files under `docs/` or `mkdocs.yml`. Press `Ctrl+C` to stop the server.

### Building the static site

To build the production site into a local `site/` directory:

```bash
uv run mkdocs build
```

Use `--strict` to fail the build on warnings such as broken internal links:

```bash
uv run mkdocs build --strict
```

## Deployment

The site is served at <https://sop4cwd.org/>.
