# Contact App — Code Snapshots

The contact application used throughout the book, captured at different stages.

| Directory        | Chapters | Description                                        |
|------------------|----------|----------------------------------------------------|
| `ch03-web10/`    | 1-3      | Web 1.0 baseline — plain HTML, no htmx             |
| `ch06-htmx/`    | 4-6      | *(placeholder)* htmx basics applied                 |
| `ch10-full/`    | 7-11     | Complete app — active search, bulk ops, archiver    |
| `ch12-hyperview/`| 12-13   | *(placeholder)* Hyperview mobile version            |

## Running a Snapshot

Each snapshot is a self-contained Flask application. To run one:

```
cd code/ch03-web10          # or ch10-full
uv run flask run
```

`uv run` will automatically create a virtual environment and install dependencies
from `requirements.txt` on first use.

If you prefer to manage the environment yourself:

```
uv venv
uv pip install -r requirements.txt
uv run flask run
```

Then open http://127.0.0.1:5000 in your browser.
