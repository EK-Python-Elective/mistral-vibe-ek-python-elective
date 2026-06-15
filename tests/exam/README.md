# Your group's tests

Put your exam feature's tests in this folder. The `Exam checks` workflow runs
`uv run pytest tests/exam` on every pull request into `main`, so a green check
means *your* tests pass — it does not run the whole upstream test suite.

You can mirror the project's structure inside here (e.g. `tests/exam/test_export.py`).

`test_placeholder.py` is just a stand-in so CI has something to run before you've
written anything — delete it once you have your own tests.
