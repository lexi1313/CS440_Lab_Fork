# Agent Instructions for TheAlgorithms/Python

## Primary Directive
You must strictly follow the rules defined in `CONTRIBUTING.md` and `AGENTS.md`.

## Task-Specific Rules (Issue #15633)
1. **Scope:** Only modify `other/password.py`.
2. **Exceptions:** Raise a `ValueError` if the requested password length is shorter than the required characters.
3. **Doctests:** Add doctests to verify both the valid length and the `ValueError` case.
4. **PR Template:** Ensure at least one checkbox is marked in the PR description to pass the `algorithms-keeper` bot.
5. **Testing:** Run `python -m doctest -v other/password.py` before committing.
