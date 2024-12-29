# uv

## Built using Rust

## Command for uv auto completion on shell
eval "$(uv generate-shell-completion zsh)"

uv init <projectname> --app
uv init <projectname> --lib
uv init <projectname> --package

uv run hello.py
uv add pandas
uv remove sqlalchemy
uv sync
uv lock
uv lock --upgrade package pandas
uv tree

uv init another_project
uv init yet-another-project --no-workspace

uv tool run ruff
uv tool run ruff check / uvx ruff check
uv tool dir
uv tool update-shell

uv tool install ruff / uv tool uninstall ruff / uv tool upgrade ruff

uv python list
uv python install 3.10.0 
uv python install '>=3.9,<=3.11'
uv venv 3.10.0

uv publish --password






