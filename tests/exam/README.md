# Your group's tests

Put your exam feature's tests in this folder. The `Exam checks` workflow runs
`uv run pytest tests/exam` on every pull request into `v2026-base`, so a green
check means *your* tests pass — it does not run the whole upstream test suite.

You can mirror the project's structure inside here (e.g. `tests/exam/test_export.py`).
The placeholder below just keeps CI green before you've written anything; replace
or add alongside it.
