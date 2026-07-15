# Contributing to Zynthetix

Thanks for your interest. These guidelines apply across Zynthetix repositories.

## Ground rules

- **Open an issue first** for anything non-trivial — describe the problem before writing code.
- **Keep changes focused.** One logical change per pull request. Small, reviewable diffs.
- **Match the surrounding code.** Follow the style, naming, and structure already present in the file.
- **Verify before you claim.** Include the test output, sample, or smoke-test evidence that shows your change works.

## Pull requests

1. Fork or branch, make your change on a topic branch.
2. Ensure existing tests pass and add tests for new behaviour.
3. Write a clear commit message: `type(scope): short description` (feat, fix, docs, refactor, test, chore).
4. Open the PR against the default branch with a description of what changed and why.

## From-scratch (AL-1) projects

The AL-1 line is intentionally dependency-light (pure NumPy core, optional CuPy). Do not introduce heavy frameworks (PyTorch, JAX) into the from-scratch core. Every autograd op must pass a gradient check; every training change must show a loss/eval number.
