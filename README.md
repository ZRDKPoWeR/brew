# Homebrew's legacy `master` branch

Homebrew uses the [`main`](https://github.com/Homebrew/brew/tree/main) branch.
Run `brew update` to migrate.

Homebrew 1.0.0 (released 21 September 2016) is the oldest version that can
bootstrap through this branch.

Without a `master` branch, Homebrew 4.5.9 (released 7 July 2025) is the oldest
version that can migrate to `main`. Installations with a stale `origin/HEAD`
may need to run `brew update` twice.

This migration will be removed on 1 March 2027.
