# Reader's Guide — gitignore

## What this project is

This is **GitHub's official collection of `.gitignore` templates** — the very
list GitHub itself uses to populate the template chooser when you create a
new repository. Each template knows which files a given language, framework,
tool or operating system generates that should never be committed (build
output, dependencies, IDE state, OS junk), so your repo stays clean from the
first commit.

## How the content is organised

- **Root templates** — 160+ files named `<Thing>.gitignore`, one per language,
  framework or platform — languages (`C.gitignore`, `C++.gitignore`,
  `Dart.gitignore`, `Elixir.gitignore`, `Erlang.gitignore`, …) and
  frameworks/tools (`Android.gitignore`, `Angular.gitignore`,
  `CMake.gitignore`, `Drupal.gitignore`, `Flutter.gitignore`,
  `Firebase.gitignore`, `CakePHP.gitignore`, `CodeIgniter.gitignore`, …).
- **`Global/`** — templates that apply across projects: operating systems and
  editors/IDEs rather than a single stack.
- **`community/`** — community-contributed templates for more specialised
  ecosystems.
- [`README.md`](README.md) — explains the collection and how the templates
  are used; [`CONTRIBUTING.md`](CONTRIBUTING.md) — the rules for proposing a
  new or corrected template (templates must be useful to a wide audience, not
  personal setups); `LICENSE` — CC0.

## How to use it

1. Find the template(s) for your stack — most projects combine one language
   template with any relevant `Global/` entries (your OS and editor).
2. Copy the contents into a file named `.gitignore` at your repository root,
   concatenating several templates if you combine stacks.
3. Commit it early — ideally before your first real commit — and adjust lines
   locally where your project differs.

## About this standalone edition

This repository is a standalone edition of
[github/gitignore](https://github.com/github/gitignore), converted from a
fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to GitHub and the
upstream contributors.
